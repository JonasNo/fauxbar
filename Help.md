# Troubleshooting #

Solutions to problems that Fauxbar may encounter.


---


## Chrome will not stay open ##

### Cause ###

There is a bug in Fauxbar v1.3.0 and v1.3.1 that can cause Chrome to close itself after you launch it.

### Solution ###

Fauxbar needs to be upgraded to v1.3.2. Here's how you can do this:

  1. Create a blank HTML file on your desktop. (you can create a blank .txt file and rename it to .html)
  1. Double-click the HTML file to open the file with Chrome; Chrome will remain open. If Chrome is not your default browser, right-click the HTML file and choose to open the file with Chrome.
  1. Open Chrome's Extensions page ( chrome://extensions ).
  1. Enable "Developer mode" at the top of the page.
  1. Click the "Update extensions now" button.
  1. After a moment, Fauxbar should restart itself and be updated to v1.3.2.

If Fauxbar does not seem to want to update to v1.3.2, here's how to temporarily resolve this bug:

  1. Open Fauxbar's Options.
  1. Under the General > Tab Override category, select Method 1 as the override method. (Method 2 is causing the bug)
  1. Close and restart Chrome.

For further details and discussion, please view [issue #138](https://code.google.com/p/fauxbar/issues/detail?id=#138).


---


## Trouble displaying site thumbnails ##

### Symptoms ###

  * Fauxbar displays a message saying:
    * "Fauxbar is having trouble displaying site thumbnails", or
    * "Fauxbar has encountered a security error. Unable to access thumbnail files.".

  * Fauxbar's site tiles no longer show their thumbnail images, even though they used to.

### Cause ###

Fauxbar is attempting to use Chrome's HTML5 FileSystem, which Fauxbar stores site thumbnails in, but Chrome is throwing a "FileError.SECURITY\_ERR" error.

This is a problem that can occur with Chrome, and is out of Fauxbar's control.

### Solution ###

To resolve this problem:

  1. Navigate to "**C:\Users\_USERNAME_\AppData\Local\Google\Chrome\User Data\Default\File System\Origins**".
  1. Delete the file named "**CURRENT**".
  1. Exit Chrome.
  1. Open Chrome.

Example screenshot of the file to delete:

![http://i.imgur.com/vBETJ.png](http://i.imgur.com/vBETJ.png)

If deleting the CURRENT file above does not work, uninstalling and re-installing Chrome should fix this problem.

For more information, or for further assistance, please refer to [issue #81](https://code.google.com/p/fauxbar/issues/detail?id=#81).