Investigation-notes.md
The destination IP 239.255.255.250 is a multicast address used by SSDP (Simple Service Discovery Protocol) under UPnP.
Alert Observed

SCAN UPnP service discover attempt
Priority: 3
Protocol: UDP
Source: 172.25.64.1
Destination: 239.255.255.250:1900

Analysis

The destination IP 239.255.255.250 is a multicast address used by SSDP (Simple Service Discovery Protocol) under UPnP.

The repeated alerts indicate periodic network discovery traffic rather than malicious scanning.

Source IP is a private internal address (RFC1918 range), suggesting local device broadcast behavior.

Conclusion

Alert classified as benign internal network discovery traffic.
No evidence of external reconnaissance or compromise
