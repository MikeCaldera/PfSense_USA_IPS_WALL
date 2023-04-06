Welcome to PfSense_USA_IPS_WALL!

This firewall setup is specifically designed to allow only USA IPs. You have the option to create exceptions for top rules if necessary. By limiting the outside traffic to a specific range of IP addresses, you can significantly reduce needless traffic that consumes costly bandwidth and server resources.

This setup is suitable for both personal and business use. It prevents outside IP addresses from accessing your web server, cameras, and other public-facing devices, thereby ensuring maximum security. It is important to lock down your outside traffic first before allowing updates from outside the USA IP address range. You can achieve this by setting a tight IP address range, rather than allowing entire countries access.

This firewall setup is free to use and highly recommended to prevent exposing your business to the potential corruption of the internet. Although even USA IPs can be rogue, setting up stick tables will help prevent denial-of-service (DOS) attacks.

In addition, this firewall setup provides real-time monitoring of your traffic. It allows you to quickly identify any attacks and determine their countries of origin.

To ensure maximum protection, enclosed are listed images from the Wan Firewall rules. Remember to create several alisas of what port(s) you want open. This allowed country and Port Alias should be used else if block everything. We know it's not 100 percent, but if you only allow ports from the USA IPs, it becomes rock solid.

Thank you for using PfSense_USA_IPS_WALL, and may God bless everyone!

