# VPN Sample Logs

## VPN Connection Event 1

### Source IP
192.168.1.10

### Source Country
United States

### Protocol
OpenVPN

### Port
1194

### UserName
admin_user

### Description
VPN connection successfully established from a remote user.

---

## VPN Connection Event 2

### Source IP
203.0.113.25

### Source Country
Germany

### Protocol
IKEv2

### Port
500

### UserName
remote_employee

### Description
VPN authentication and encrypted tunnel established successfully.

---

## VPN Connection Event 3

### Source IP
198.51.100.42

### Source Country
Russia

### Protocol
PPTP

### Port
1723

### UserName
unknown_user

### Description
Repeated VPN connection attempts detected from an unusual geographic location.

---

## VPN Connection Event 4

### Source IP
172.16.20.5

### Source Country
India

### Protocol
L2TP

### Port
1701

### UserName
vpn_support

### Description
VPN session established for remote administrative access.

---

## Monitoring Purpose
These sample VPN logs were analyzed using Elastic Stack and Kibana dashboards to monitor:
- VPN connection trends
- Source IP activity
- Geographic access patterns
- Protocol usage
- Suspicious connection behavior
