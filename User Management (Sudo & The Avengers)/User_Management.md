sudo: SuperUser Do.

Hack Example: sudo -l (List permissions). This shows what commands you can run as root without a password—a common path to privilege escalation.

visudo: The safe way to edit the sudoers file.

Example: Adding user ALL=(ALL) NOPASSWD: ALL gives that user total root power without ever asking for a password.

useradd vs adduser:

useradd is a binary (low level); adduser is a script (friendly).

Example: sudo useradd -m -s /bin/bash hacker creates a user with a home folder and a bash shell.