# Network Information Batch Script

This is a simple batch script for Windows that displays all current TCP/IP network configuration values and refreshes Dynamic Host Configuration Protocol (DHCP) and Domain Name System (DNS) settings.

## Usage

1. Open a command prompt with administrative privileges.
2. Navigate to the directory containing the `Network Information.bat` file.
3. Run the script by typing `Network Information.bat` and pressing Enter.

## What the Script Does

Here's a breakdown of what each line in the script does:

```bat
@echo off             # Prevents the command prompt from displaying the commands in the script as they run
ipconfig.exe /all     # Displays all current TCP/IP network configuration values and refreshes DHCP and DNS settings
pause                 # Waits for the user to press a key before closing the command prompt window