# Installing the Griffon Virtual Machine

## Prerequisites
The Griffon VM requires a computer with at least 8GB of RAM and we recommend at least 40 GB of hard disk space.  Prior to installing Griffon, you will need to install VirtualBox which is available here: https://www.virtualbox.org.

Once you have installed VirtualBox, you will also need something to decompress a 7-zip file.  For Windows machines, we recommend 7-zip (http://www.7-zip.org/download.html), for Mac you'll need Keka (http://www.kekaosx.com/en/) and 

### Linux 
Install p7zip to unzip *.7z files on Fedora
```  
  $ yum install p7zip
```
On Debian and Ubuntu
```
$ sudo apt-get install p7zip
```

## Installing Griffon in VirtualBox
Once you have VirtualBox installed, the next step is to unzip Griffon.  Once you've done that, open VirtualBox.  The screen shots shown below are from a Mac, but the process should be fundamentally the same for all systems.

### Step 1.  Import the VM
Navigate to the *File* menu and click on *Import Appliance*

![alt text](https://github.com/gtkcyber/griffon-vm/blob/master/images/import-menu.png "Import Appliance Menu")

Next, navigate to the file you just unzipped which contains the Griffon VM and click Continue.

![alt text](https://github.com/gtkcyber/griffon-vm/blob/master/images/step1.png "Import Appliance Dialog Box")

Once you've done that, the next screen will allow you to configure the VM.  If you are using Griffon to experiment with the various big data tools, we recommmend allocating as many CPUs and as much RAM as your system will allow. **Be sure to check the Reinitialize MAC Address box.**

![alt text](https://github.com/gtkcyber/griffon-vm/blob/master/images/step2.png "Configure Griffon Dialog Box")

Click continue, accept the license, and VirtualBox will install the appliance!
