SUMMARY

This folder contains the scripts and programs used to create and refresh the background information (bginfo.exe) wallpaper. The background is updated by execution of the "run.bat" script. That script uses settings from the "default.bgi" file. The script is run by the OS during startup. That function is controlled by use of the following registry entry:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run\bginfo

SETUP

1. Deploy this archive to the "%SystemDrive%\Program Files (x86)\Microsoft\BGInfo"
2. Run the "startup.reg" registry file by double clicking on it.

