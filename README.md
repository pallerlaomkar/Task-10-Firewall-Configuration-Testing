# Task 10: Firewall Configuration & Testing

## Objective
Configure and test firewall rules using UFW to control network traffic and improve system security.

## Tools Used
- UFW (Uncomplicated Firewall)
- Nmap
- iptables

## Steps Performed
1. Enabled UFW and set default policies (deny incoming, allow outgoing).
2. Allowed SSH (22), HTTP (80), and HTTPS (443).
3. Blocked port 8080.
4. Blocked malicious IP: 192.168.1.100.
5. Allowed trusted IP: 192.168.1.50.
6. Tested rules using Nmap.
7. Enabled firewall logging.
8. Verified rules using iptables.

## Observations
- Allowed ports appeared filtered externally due to firewall rules.
- Blocked ports and IPs were inaccessible.
- Logs confirmed firewall actions.

## Final Outcome
Hands-on firewall management and testing skills.
