systemctl status [service]: Check if a service is running.

Example: systemctl status ssh. If it's "active," the machine is listenning for connections.

systemctl enable [service]: Makes the service start automatically on boot.

journalctl -u [service]: View the specific logs for just that service.

Example: journalctl -u apache2 to see why a web server crashed.