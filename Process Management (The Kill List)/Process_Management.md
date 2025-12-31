ps aux: The "Snapshot." Shows every process running right now.

Example: ps aux | grep root shows only processes running as root.

htop: The "Dashboard." Visual interface to manage CPU/RAM.

kill -9 [PID]: The "Assassin." Force-kills a process.

Example: If a script is hanging, find its PID and use -9 to terminate it without cleanup.

jobs & fg: Manage background tasks.

Example: Run a scan, hit Ctrl+Z to pause, type bg to run it in background, then fg to bring it back later.