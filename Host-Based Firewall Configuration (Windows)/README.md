# Host-Based Firewall Configuration (Windows)

## 🔹 Project Overview
This project demonstrates the configuration of a **host-based firewall** on a Windows machine. The goal was to restrict unauthorized network traffic and allow only approved services, improving endpoint security.

## Objectives
- Understand the role of host-based firewalls in endpoint protection.  
- Configure inbound and outbound firewall rules.  
- Test firewall rules against simulated attacks and normal traffic.  

## Process
1. Opened **Windows Defender Firewall with Advanced Security**.  
2. Configured **Inbound Rules**:  
   - Allowed essential services (HTTP, HTTPS, RDP).  
   - Blocked unnecessary ports (e.g., Telnet, FTP).  
3. Configured **Outbound Rules**:  
   - Restricted applications from making external connections.  
   - Allowed trusted apps (e.g., browsers, VPN client).  
4. Tested firewall rules by:  
   - Attempting to access blocked ports.  
   - Running `ping`, `telnet`, and custom apps.  
   - Monitoring logs in **Event Viewer**.  
5. Documented blocked and allowed traffic.  

## Deliverables
- Screenshots of firewall rules.  
- Test results showing blocked/allowed traffic.  
- Documentation of firewall configuration.  

## Skills Demonstrated
- Endpoint security configuration.  
- Network traffic control.  
- Windows administrative tools.  

## Tools Used
- Windows Defender Firewall with Advanced Security  
- Event Viewer  
- Command line utilities (ping, telnet, netstat)  
