# putty-ssh-command-windows
A very simple Windows program that allows you to use the ssh command directly from CMD.

## Set Up
1. Download ssh.bat, and, if you you have not already done so, "putty.exe" from http://www.putty.org/

2. Create a folder in "C:\Program Files (x86)" named "Putty".

3. Copy the "putty.exe" and "ssh.bat" executables into the new folder.

4. Next, you have to add this folder to the PATH. Go to Control Panel, then System and Security, then System, then Advanced System Settings. You can also get there by searching path in the start menu search bar.

5. Then click environment variables and select PATH under "User Variables for your-username".

6. Click Edit, then in the popup window click New and enter "C:\Program Files (x86)\putty" (without the quotation marks) into the text box.

7. Then click OK on all of the windows to close them.

__Now you can use ssh from the windows comand-line, just like you would on Linux. Just type "ssh username@hostname".__
