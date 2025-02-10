# Convert-WindowsImage

Script for converting ISO and WIM files to VHD

This is a fork of Convert-WindowsImage from the TechNet Script Center: <https://gallery.technet.microsoft.com/scriptcenter/Convert-WindowsImageps1-0fe23a8f>

This code is owned by Microsoft and licensed under the MS-LPL.  See the LICENSE file for more information.

## Changes from the Script Center version

- Fix for the following error on Window 10 version 1709:

  ```plain
  ERROR  : Exception calling "Apply" with "1" argument(s): "The directory or file cannot be created"
  ```

- Make it executable as a script, by typing `.\Convert-WindowsImage.ps1`. This is done through binding parameters at the script level, instead of declaring a function inside the script.
