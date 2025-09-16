# networking-cybersecurity-projects
# Advanced CCNA Networking & Cybersecurity Project

This project was fully designed and implemented by me in **Cisco Packet Tracer**, without automation, external assistance, or teammates.  
It represents a complex enterprise-level network that integrates switching, routing, WAN, wireless, and advanced cybersecurity practices.

---

## 🔹 Project Overview
The network simulates an enterprise environment with multiple departments, branch sites, and secure services.  
It integrates VLAN segmentation, WAN connectivity, VPN, monitoring, and advanced Layer 2/3 security mechanisms.

---

## 🔹 Implemented Features & Skills

### 🔐 Security & Access Control
- **SSH enabled** for secure remote access (Telnet disabled).  
- **Password encryption**, domain name, and RSA key generation.  
- **AAA authentication** using TACACS+ and RADIUS.  
- **Login banners**, console/aux protections, and disabled DNS lookup.  
- **ACLs** (standard and extended) for service filtering.  
- **VPN tunnels** for branch connectivity.  
- **SNMP** and **Syslog** for monitoring.  
- **Port Security**, **BPDU Guard**, **PortFast**, and **STP priority** for L2 hardening.  
- **Dynamic ARP Inspection**, **DHCP Snooping**, and IP Source Guard.  
- **Port Mirroring** for packet capture.  

### 🖧 Switching & VLANs
- Multiple **VLANs** for segmentation (users, servers, VoIP, wireless).  
- **Router-on-a-Stick** inter-VLAN routing.  
- **Layer 3 switch routing** with OSPF.  
- **EtherChannel** for redundancy and load balancing.  
- **VTP** for VLAN distribution.  
- **Root bridge** optimization for STP.  

### 🌐 Routing & WAN
- **OSPF dynamic routing** with reference bandwidth tuning.  
- **Static routes** and **default routes** for Internet access.  
- **NAT/PAT overload** for secure external connectivity.  
- **DHCP relay (IP helper)** for remote VLANs.  
- **Loopback interfaces** for stability and testing.  
- **FHRP (First Hop Redundancy Protocols)** for gateway resilience.  

### 📡 Wireless & Mobility
- **Wireless LAN Controller (WLC)** managing wireless clients.  
- Secure SSID mapping to VLANs.  
- Laptops and smartphones connected to wireless networks.  

### 🖥️ Network Services
- **DHCP**, **DNS**, **Email (SMTP/POP3/IMAP)**, **HTTP/HTTPS**, and **TFTP** servers.  
- **NTP** server for time synchronization.  
- **Syslog** integration for centralized logging.  
- **Debug and Logging** enabled across devices.  

### 🛡️ Firewall & DMZ
- **DMZ segment** with public-facing servers:  
  - Web server (`www.omri.com`, `https://www.the-internet.net`)  
  - Mail server  
  - Public DNS server  
- Strict ACLs isolating DMZ from internal networks.  

---

## 🔹 Documentation
- **Description applied to all ports** for clarity.  
- Topology exported as `screenshot.png`.  
- Device configurations stored in `configs/`.  
- Security design decisions documented in this README.  

---

## 🔹 Skills Demonstrated
- Enterprise network design and documentation.  
- Routing & Switching: VLANs, OSPF, trunking, router-on-a-stick, EtherChannel.  
- Cybersecurity: ACLs, VPN, NAT/PAT, DHCP Snooping, ARP inspection, TACACS+, RADIUS, port security.  
- WAN technologies: DHCP relay, loopback routing, FHRP.  
- Services: DHCP, DNS, Email, HTTP/HTTPS, TFTP, NTP, Syslog, SNMP, VoIP.  
- Troubleshooting, monitoring, and hardening practices.  

---

## 📂 Repository Structure
- `advanced_project.pkt` → Packet Tracer project file.  
- `configs/` → Router & switch configuration scripts.  
- `screenshot.png` → Network topology diagram.  
- `README.md` → Documentation (this file).  

---

## ✅ Conclusion
This project demonstrates my ability to design, secure, and manage a **complex enterprise-grade network**, integrating advanced CCNA-level concepts with cybersecurity best practices.  
All work was completed independently and reflects both technical depth and practical implementation.
