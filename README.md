# VRChat Ban Checker
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

# F.A.Q
1. It says that "Youre trying to login from another location!".
A. That means, that you either need to verify the login for your account or to make sure that you use for example a german ip with a german VRChat account.
2. StatusCode 429 = Too many Requests!
A. That can happen because the API already got many requests from your IP and is blocking it for a period of time. Hang tight and retry it later.

# Disclaimer
This program is for educational purposes only. Do not use it to access VRChat accounts without the owners' permission. The developers of this program are not responsible for any illegal activities or misuse of the program...
Also there is NO Proxies in the code.. Its hard to find any free Proxies that didnt got banned from VRChat... Thats why this one will be WITHOUT. It will run through your own IP. Be adviced that if you use more than 1 account that a ross-ban could happen. If you want to modify it feel free to contact me (Keith#1337)
#
