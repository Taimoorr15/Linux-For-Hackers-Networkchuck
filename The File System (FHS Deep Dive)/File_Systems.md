/etc: The "Gold Mine." Contains configuration files.

Hack Example: cat /etc/passwd lists all users.

/var/log: Where the "Snitch" lives. Contains all system logs.

Hack Example: Check /var/log/auth.log to see failed login attempts.

/tmp: The "Scratchpad." Usually has write permissions for everyone.

Hack Example: Download your exploit scripts to /tmp because the system usually allows execution there.

/bin & /sbin: Essential binaries.

Example: ls /sbin shows admin-only tools like iptables or fdisk.