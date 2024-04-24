# Dragon
Dragon is a file password recovery tool and Linux shadow file cracker. 
It uses the dictionary search or Brute force method for cracking passwords.
## Supported Files
*	RAR Files
*	Legacy ZIP Files
*	PDF Files
*	Linux Shadow Files (Dragon can find all the user’s password in the linux shadow file one after the other)
## Prerequisites
To run the app, minimal requirements are:
*	Python 3.3 or higher
*	debian-based linux distro, preferably Kali linux 2
*	**qpdf** and **unrar** packages<br /> Installing these packages on kali is as easy as running the following commands on terminal:
<br />```$ sudo apt-get update```
<br />```$ sudo apt-get install qpdf unrar```
*	some python modules in this program need to be installed manually, like:
zipfile, rarfile, crypt, pyfiglet, py-term(for term module) and so on.
you can use pip3 for install them
example: <br />```$ pip3 install py-term```
<br />**notice**: rar,zip and pdf files must have an extension, shadow files does not need an extension.
*   Install figlet font "epic" if it does not exists on your system:
<br/> ```sudo wget http://www.figlet.org/fonts/epic.flf -O /usr/share/figlet/epic.flf```

## Features
*	Cracking files password using two methods:  **1.** dictionary method **2.** brute force method
*	In the brute force method, you can specify the min length and max length of the passwords.
*	 In the brute force method, you can specify the type of characters that may be used in the password.
*	There is a percent progress bar showing how much of the process has been performed.
*	Error handling.
*	One of the most important features of Dragon is the multiprocessing feature that speeds up the program. For example if you have 8 CPU cores, Dragon will use all of them for processing at the same time.
## Installation
Download Dragon by cloning the Git repository:
  <br />```$ https://github.com/HIRU1920/Dragon-Bruteforce```
  
You can also use [vagrant](https://www.vagrantup.com/) to automatically install and run Zydra (more information at the bottom of the page).
## Usage
To get a list of all options and learn how to use this app, enter the following command:<br />
  <br />```$ python3 Dragon.py -h```

  ## Author

* **Hir Patel** 

## License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/hamedA2/Zydra/blob/master/LICENSE) file for details
 		
