# VRChat Login
A simple C# program to check the status of VRChat users.
#

# Features
Reads a list of usernames and passwords from a file (usernames.txt)
Makes a request to the VRChat API to check if the user is active or banned
If the user is banned, sends a message to a specified Discord webhook (the URL is read from a file webhook.txt)
Waits for 30 minutes before checking the status of the next user
#

# Requirements
.NET Framework 4.5 or higher
#

# Usage
download the .exe in the release section.
Create a file called usernames.txt in the same directory as the executable
Add each VRChat username and password to the file, separated by a colon (e.g. username:password)
Create a file called webhook.txt in the same directory as the executable and add the URL of the Discord webhook to it
Run the program
#

# Disclaimer
This program is for educational purposes only. Do not use it to access VRChat accounts without the owners' permission. The developers of this program are not responsible for any illegal activities or misuse of the program.
#
