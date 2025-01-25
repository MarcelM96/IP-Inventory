# IP-Inventory
 script scans your local network to detect active devices, logs their IP addresses, and attempts to resolve their hostnames. Instead of manually specifying an IP range, the script automatically calculates the network range based on the IP address of your local device and performs a scan to find other devices connected to the same network.


Key Features:
No Need for Manual Range Input: The script asks for the IP address of your local device, then automatically calculates the range of IP addresses in the same network.
Scans the Network: It checks all IP addresses within the calculated network range to find active devices.
Logs Active Devices: The script logs the devices that respond to ping requests, displaying their IP address and, if available, their hostname.
Platform-independent: Works on both Windows and Linux environments.
Fast and Efficient: Uses Python’s concurrent.futures.ThreadPoolExecutor to scan the network in parallel, making the process faster and non-blocking.
