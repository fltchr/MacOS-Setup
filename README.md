# MacOS-Setup
This project details the steps to be completed for setup of a new MacOS device. As with many such projects like this on GitHub, the steps/needs below are higly specific and may not work in all circumstances or for all users.

1. Install and Update MacOS

 The latest version of MacOS should be downloaded from the Mac App Store and transferred to a USB Drive.
  1. Download the MacOS installer from the Mac App Store.
  1. Prepare the USB Media.
    1. Connect a USB drive of at least 8GB to the Mac.
    1. Launch Disk Utility.
    1. Select the USB drive from the device tree on the left hand side.
    1. Click "Erase" from the toolbar.
    1. Enter a description name (i.e. "macOS Sierra Installer").
    1. Confirm "OS X Extended (Journaled) is selected for Format.
    1. Confirm "GUID Partition Map" is selected for Scheme.
    1. Click "Erase" and wait for the process to complete.
  1. Launch Terminal.app
  1. Enter the following command within terminal:
    *installerpath*/createinstallmedia --volume *volumepath* --applicationpath *installerpath*
  1. Wait for the process to complete. It may take upwards of 30 minutes.
  
 Install MacOS to the Mac using the USB drive.
  1. Connect the USB drive with the macOS installer to the Mac.
  1. Hold down option key while rebooting the Mac.
  1. Select the USB drive and wait for the installer to load.
  1. Launch Disk Utility.
  1. Select the built in drive and click "Erase" from the toolbar.
  1. Enter "OSX" for the description.
  1. Confirm "OS X Extended (Journaled) is selected for Format.
  1. Confirm "GUID Partition Map" is selected for Scheme.
  1. Click "Erase" and wait for the process to complete.
  1. Close Disk Utility.
  1. Click "Install macOS".
  1. Select the partition labelled "OSX" and click install.
   
