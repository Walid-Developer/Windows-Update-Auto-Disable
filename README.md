# Windows-Update-Auto-Disable

If you want the batch file to run automatically when Windows starts up, you can achieve this by placing a shortcut to the batch file in the Windows Startup folder. Here's how you can do it:

Locate the Batch File: Ensure that your batch file (e.g., DisableWindowsUpdate.bat) is in a location where you can easily find it.

Create a Shortcut:

Right-click on the batch file.
Select "Create shortcut."
Access the Startup Folder:

Press Win + R to open the Run dialog.
Type shell:startup and press Enter. This will open the Startup folder.
Place the Shortcut:

In the Startup folder, paste the shortcut you created earlier. You can do this by right-clicking inside the folder and selecting "Paste."
Test It:

Restart your computer or log out and log back in.
The batch file should now run automatically when Windows starts up.
Please keep in mind that running a script that disables Windows Update on startup is not recommended for long-term use, as it can leave your system vulnerable to security risks. Only use this approach if you have specific, temporary reasons to disable Windows Update.
