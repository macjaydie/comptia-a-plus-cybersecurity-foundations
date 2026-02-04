# Network Troubleshooting



Network issues can prevent access to the internet or local resources. Troubleshooting involves checking both physical and logical components.



---



## No Internet Connection



Possible causes:

- Loose or unplugged cables

- Router or modem failure

- Incorrect IP configuration



Steps to troubleshoot:

- Check physical connections

- Restart modem and router

- Run ipconfig /all to verify IP address



---



## IP Address Issues



An incorrect IP address can prevent communication.



Steps to troubleshoot:

- Use ipconfig /release and ipconfig /renew

- Ensure DHCP is enabled

- Assign a correct static IP if required



---



## DNS Problems



DNS issues prevent websites from loading.



Steps to troubleshoot:

- Try accessing a site by IP address

- Flush DNS cache using ipconfig /flushdns

- Change DNS server to a public DNS like 8.8.8.8



---



## Slow Network Speeds



Possible causes:

- Weak Wi-Fi signal

- Network congestion

- Malware using bandwidth



Steps to troubleshoot:

- Move closer to the router

- Disconnect unnecessary devices

- Scan for malware



---



## Testing Connectivity



Common commands:

- ping to test reachability

- tracert to trace network path

- netstat to view active connections
