# Chapter 7: Installing Linux in the Virtual Machine

In this chapter, you will install Sparky Linux to the virtual machine and then save a snapshot of this initial post-installation state.

## Procedure
* Boot up your virtual machine with Sparky Linux, just as you did in the previous chapter.
* Double-click on the "Sparky Installer" icon.  (Use the regular installer, not the advanced installer or online installer.)
* When prompted, select your language, region, time zone, and keyboard.
* When you are in the Partitions section, you will be asked whether you wish to erase the disk (so that it will be used entirely for your new Sparky Linux installation) or to do manual partitioning (useful for dual booting).  Select the option to erase the disk.  Use the default boot loader location (Master Boot Record), and click on "Next".
* Enter your name, username, name of computer, and password.  (You may use "rubyonracetracks" for the computer name.)  Toggle off the option to log in automatically.  Click on "Next" to continue.
* Check the parameters in the summary section.  If they are correct, click on "Next" to continue.
* The installation process will now begin and take several minutes to complete.  How long this takes depends on the speed of your computer.
* After the installation process is completed, click on "Quit".
* Click on Menu -> Logout and select "Shutdown".
* Remove the ISO file from the virtual optical drive.  This is the virtual equivalent of ejecting the DVD from the optical drive.
  * Once the virtual machine has been shut down and you are back in the VirtualBox main screen, select "SparkyLinux", click on "Settings", and click on "Storage".  
  * Select the SparkyLinux ISO file (under "Controller: IDE"), click on the disc symbol, and select the "Remove Disk from Virtual Drive" option.  The virtual IDE controller should now be empty.
  * Click on "OK" to return to the VirtualBox main screen.
* Take a snapshot of the virtual machine's current state.
  * From the VirtualBox main screen, select "SparkyLinux" and click on "Snapshots".
  * Click on the camera symbol to take a snapshot of the current state.  Use the name "Initial installation" for this snapshot.
  * Now you have saved the initial post-installation state of your SparkyLinux virtual machine.  If you ever want to or need to return your virtual machine to this state, you can restore this snapshot rather than reinstall SparkyLinux.
