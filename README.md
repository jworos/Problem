# ProblemSets

Sent icmp packets (Ping) to these sites using terminal, and retrieved their static IP addresses;

1. Google.com - 216.58.223.238
2. Facebook.com - 102.132.101.35
3. Amazon.com - 176.32.103.205
4. herokuapp.com - 54.160.84.228

Scanned the ports of the sites using the Zenmap standalone app, and connected successfully to all the ports using terminal.

Ports on Google.com

21/Ftp - Open
25/Smtp - Open
80/Http - Open
443/ Https - Open 
587/Submission - Open

Ports on Facebook.com 

21/Ftp - Open
25/Smtp - Open
80/Http - Open
443/ Https - Open 
587/Submission - Open
843/Unknown - Closed
5222/Xmpp-client - Closed

Ports on Amazon.com

Amazon came up with 3 IP addresses after scanning:

1. 176.32.103.205
2. 205.251.242.103
3. 54.239.28.85 - this IP came up with 13 filtered ports

21/Ftp - Open
25/Smtp - Open
80/Http - Open
443/ Https - Open 
587/Submission - Open

Ports on Herokuapp.com
Amazon came up with 3 IP addresses after scanning:
1. 54.160.84.228
2. 52.200.177.141

21/Ftp - Open
25/Smtp - Open
80/Http - Open
443/ Https - Open 
587/Submission - Open

Tested all open ports, also tested the closed port from Facebook.com, but that didn’t connect.

Created a new Git Repo, cloned it using terminal, edited the README.md file in VSCODE, and commited the edit using terminal after saving on VsCode.
