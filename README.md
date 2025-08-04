The target IP address that was scanned, which in this case is 
192.168.0.131.

The Nmap command used, 
nmap -sS 192.168.0.131.

The scan report, which indicates the host is "up".

A list of the four open ports found: 100, 135, 139, and 445.

The services identified for each port: 
newacct for port 100, msrpc for port 135, netbios-ssn for port 139, and microsoft-ds for port 445.

A discussion of the risks and disadvantages associated with each open port. For example, the 
newacct service on port 100 is noted for "unauthorized use" and its security is unknown. Port 135 (MSRPC) has a history of vulnerabilities that can be exploited by malware. Ports 139 and 445 have been famously targeted by ransomware like WannaCry.

The importance of securing these open ports, for instance, by blocking them at the perimeter firewall and ensuring systems are patched.






