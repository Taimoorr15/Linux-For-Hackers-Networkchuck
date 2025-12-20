whoami: Identifies your current privilege level.
Example: If you exploit a web server and type whoami, it might return www-data. You then know you need to privilege escalate to root.

pwd: Print Working Directory.
Example: pwd returns /var/www/html. You now know exactly where to upload your web shell.

ls: List directory contents.
Example: If you type ls in a directory, it will list all the contents in that directory for you

Switches: ls -la (List All + Long format).
Example: ls -la reveals hidden files like .bash_history which might contain passwords left by an admin.

cd: Change Directory.
Example: cd / (Go to root), cd ~ (Go home), cd - (Go to the previous folder you were in).