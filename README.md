# Networks_and_Network-Security
# 🌐 Network Components, Devices, and Diagrams

> Comprehensive cybersecurity and networking notes to understand core network architecture, devices, protocols, and use cases.

---

## 📶 Modem

✅ **Description**  
A modem (modulator-demodulator) connects a local network to the internet through an ISP (Internet Service Provider). It converts analog signals from the ISP into digital signals that your router and local network can understand.

🧠 **Example**  
A cable modem provided by your ISP converts the signal from a coaxial cable into Ethernet, which connects to your home router.

🎯 **Use Case**  
Essential for small businesses and homes to access the internet via broadband, DSL, or fiber.

⚡ **Tips**  
- Business/enterprise networks usually skip modems and use leased lines or fiber directly.
- Always secure modem access through a strong password to avoid unauthorized changes.

![Network Devices Diagram](![Screenshot 2025-06-16 012117](https://github.com/user-attachments/assets/6306259a-9992-46f1-8621-32a511999eb3)
)

---

## 📡 Wireless Access Point (WAP)

✅ **Description**  
A wireless access point is a device that creates a Wi-Fi network, allowing wireless devices to connect to a wired network. It acts like a hub for wireless communication.

🧠 **Example**  
An office uses multiple WAPs spread across floors so laptops and mobile devices can connect to the company’s intranet wirelessly.

🎯 **Use Case**  
Used in schools, enterprises, cafes, and homes to provide wireless access.

⚡ **Tips**  
- Place WAPs strategically for full coverage and minimum interference.
- Use WPA3 encryption to secure wireless traffic.

![Modem and Connectivity](![Screenshot 2025-06-16 012319](https://github.com/user-attachments/assets/c2f0e0d5-8aff-4a52-904a-88b0ac910d98)
)

---

![Wireless Access Point](![Screenshot 2025-06-16 012414](https://github.com/user-attachments/assets/648ff449-62ec-4000-95b7-7478fc9a783f)
)

---

## 🔌 Switch

✅ **Description**  
A switch connects multiple devices within a network and intelligently forwards data only to the device it’s intended for, using MAC addresses. Operates at Layer 2 (Data Link) of the OSI model.

🧠 **Example**  
A 48-port managed switch in a corporate server room connects employees’ computers, printers, and VoIP phones.

🎯 **Use Case**  
- Efficient LAN traffic management
- VLAN segmentation
- Minimizing broadcast traffic

⚡ **Tips**  
- Use managed switches in enterprise environments to control VLANs, QoS, and port mirroring.
- Unlike hubs, switches reduce collisions and improve security.

---

## 📎 Hub

✅ **Description**  
A basic, outdated device that connects multiple computers in a LAN and sends incoming data to all devices, regardless of destination.

🧠 **Example**  
In a 4-port hub, if one computer sends data, all four ports receive it.

🎯 **Use Case**  
Now obsolete—mainly used for lab demonstrations or legacy systems.

⚡ **Tips**  
Avoid hubs in any modern or secure network. They are prone to packet sniffing.

---

## 🌍 Router

✅ **Description**  
Routers connect different networks and direct packets based on IP addresses. They operate at Layer 3 (Network Layer) of the OSI model.

🧠 **Example**  
A home router connects your LAN to the internet, assigns IPs to devices, and directs traffic to and from the modem.

🎯 **Use Case**  
- Connecting LANs to WANs
- NAT (Network Address Translation)
- DHCP and firewalling

⚡ **Tips**  
- Secure routers with strong admin credentials and firmware updates.
- Use dual-band routers for better bandwidth distribution.

---

## 🔥 Firewall

✅ **Description**  
A firewall monitors and filters incoming and outgoing network traffic based on pre-set security rules. It acts as a gatekeeper between internal and external networks.

🧠 **Example**  
An enterprise firewall blocks all incoming traffic except ports 443 and 80 for HTTPS and HTTP.

🎯 **Use Case**  
- Prevent DDoS attacks
- Block IPs/domains
- Control employee access to apps/sites

⚡ **Tips**  
- Use both hardware and software firewalls for layered protection.
- Implement logging and alerting for suspicious traffic.

---

## 🖥️ End-User Devices (Desktops, Laptops, Mobiles)

✅ **Description**  
These are the client devices that connect to the network. Each device uses a network interface card (NIC) with a unique MAC address and gets an IP via DHCP.

🧠 **Example**  
Your smartphone connects to Wi-Fi, receives an IP from the router, and accesses Google.com via HTTPS.

🎯 **Use Case**  
Used to consume services—browse web, access mail, share files.

⚡ **Tips**  
- Keep OS and antivirus updated.
- Disable unused ports and services for hardening.

---

## 🗄️ Server

✅ **Description**  
A server provides services or resources (files, mail, DNS, web) to client devices over a network. Works under the client-server model.

🧠 **Example**  
A web server hosts your personal portfolio and handles requests via HTTP/HTTPS.

🎯 **Use Case**  
- Central file storage
- Web hosting
- Authentication (e.g., LDAP server)

⚡ **Tips**  
- Regularly back up data and monitor access logs.
- Use firewalls, IDS, and strong access policies.

![Server and Client-Server Model](![Screenshot 2025-06-16 012200](https://github.com/user-attachments/assets/947f6761-90cf-46bf-b927-c5136ed4e725)
)

---

## 🔁 Client-Server Model

✅ **Description**  
The architecture where a client requests resources and the server responds. This model is the backbone of web services and business apps.

🧠 **Example**  
When you access YouTube, your browser (client) sends a request and YouTube's server responds with video content.

🎯 **Use Case**  
- Web browsing
- Cloud storage
- Email communication

⚡ **Tips**  
- Optimize server load with load balancers.
- Secure communication using TLS/SSL.

---

## 🧾 Network Diagrams

✅ **Description**  
A visual representation of a network’s layout—how devices like routers, firewalls, switches, and endpoints are connected.

🧠 **Example**  
A diagram shows the internet connected to a modem > firewall > router > switch > devices.

🎯 **Use Case**  
- Visualize traffic paths
- Plan segmentation
- Troubleshooting

⚡ **Tips**  
- Always maintain updated network diagrams.
- Use icons and layers for clarity (physical vs logical).

![Network Diagram Example](![Screenshot 2025-06-16 012442](https://github.com/user-attachments/assets/729a09cd-1261-4aaf-9fc1-f994bc47df65)
)

---

## 🧠 Key Takeaways

- **Routers** route data between networks, **Switches** within networks.
- **Firewalls** are crucial for perimeter defense.
- **Servers** deliver resources, **clients** consume them.
- Avoid **hubs**, prefer **switches** for performance and security.
- Diagrams aid in understanding and defending your network layout.

---

## 🛠️ Recommended Tools

- 🧪 **Wireshark** – Packet analysis
- 🔍 **Nmap** – Network scanning
- 🧱 **Cisco Packet Tracer** – Simulations
- 🎨 **Draw.io** / **Lucidchart** – Network diagrams
- 📊 **Nagios/Zabbix** – Network monitoring

---

🛡️ **Pro Tip**  
Apply the principle of **defense in depth**: use firewalls, endpoint protection, network segmentation, strong passwords, and regular monitoring.

---

🧠 Made with precision for cybersecurity learners.


# 🌐 Network Models: TCP/IP and OSI — A Complete Guide

Welcome to the ultimate GitHub-ready cheat sheet on **TCP/IP and OSI models**! This guide breaks down complex networking concepts into clear and practical explanations with useful examples, tips, and real-world use cases.

---

## 📦 What Are Networking Models?

**Networking models** are conceptual frameworks that help explain how data moves across networks. The two most widely used models are:

- **TCP/IP Model** (used in real-world internet communication)
- **OSI Model** (theoretical model used for teaching and troubleshooting)

---

# 🧱 The OSI Model (7 Layers)

The **OSI (Open Systems Interconnection)** model describes how data is transmitted in seven steps (or layers).

We’ll go from **Layer 7 (closest to user)** down to **Layer 1 (closest to hardware)**.

---

## 7️⃣ Application Layer

- ✅ **Description**: Interfaces directly with the end user. Supports services like web browsing, email, and DNS.
- 🧠 **Example**: Accessing a website using a browser with HTTP.
- 🎯 **Use Case**: Sending/receiving emails, browsing the internet, file transfers.
- ⚡ **Tips**: Protocols like `HTTP`, `HTTPS`, `SMTP`, and `DNS` work here.

---

## 6️⃣ Presentation Layer

- ✅ **Description**: Translates, encrypts, or compresses data for application layer.
- 🧠 **Example**: Converting video formats, SSL encryption (HTTPS).
- 🎯 **Use Case**: Data format translation (e.g., JPEG to PNG), secure communications.
- ⚡ **Tips**: Encryption like `SSL/TLS` happens here.

---

## 5️⃣ Session Layer

- ✅ **Description**: Manages sessions or conversations between computers.
- 🧠 **Example**: Login session management on a website.
- 🎯 **Use Case**: Maintaining live connections (e.g., Zoom, online games).
- ⚡ **Tips**: Handles reconnections, checkpoints, authentication.

---

## 4️⃣ Transport Layer

- ✅ **Description**: Breaks data into smaller segments, ensures reliable delivery.
- 🧠 **Example**: Using `TCP` to ensure reliable file download.
- 🎯 **Use Case**: Email transfer (reliable), video streaming (fast but less reliable).
- ⚡ **Tips**: `TCP` = reliable, `UDP` = faster but unreliable.

---

## 3️⃣ Network Layer

- ✅ **Description**: Adds IP addresses and routes data between networks.
- 🧠 **Example**: Routers forwarding packets using IP addresses.
- 🎯 **Use Case**: Routing data across cities, countries.
- ⚡ **Tips**: `IP`, `ICMP` protocols operate here.

---

## 2️⃣ Data Link Layer

- ✅ **Description**: Transfers data between devices on the same network.
- 🧠 **Example**: A switch directing data between PCs on a LAN.
- 🎯 **Use Case**: Local network communication via MAC addresses.
- ⚡ **Tips**: Ethernet, MAC, switches belong here.

---

## 1️⃣ Physical Layer

- ✅ **Description**: Physical transmission of bits over media.
- 🧠 **Example**: Data over an Ethernet cable or fiber optic.
- 🎯 **Use Case**: Wi-Fi, Cables, Modems, NICs.
- ⚡ **Tips**: Deals with 1s and 0s — the actual signal.

---

# 🧳 The TCP/IP Model (4 Layers)

The **TCP/IP model** is a simplified, practical version of the OSI model, with only four layers. It's what the internet actually uses.

---

## 1️⃣ Network Access Layer (Like OSI Layer 1 + 2)

- ✅ **Description**: Handles physical hardware and data link tasks.
- 🧠 **Example**: Sending data via Ethernet with MAC address.
- 🎯 **Use Case**: Local device communication, MAC address resolution.
- ⚡ **Tips**: Protocols: `Ethernet`, `ARP`

---

## 2️⃣ Internet Layer (Like OSI Layer 3)

- ✅ **Description**: Adds IP addresses, routes packets.
- 🧠 **Example**: Sending a message across multiple networks using `IP`.
- 🎯 **Use Case**: Cross-network communication.
- ⚡ **Tips**: Protocols: `IP`, `ICMP`

---

## 3️⃣ Transport Layer (Same as OSI Layer 4)

- ✅ **Description**: Ensures reliable or fast delivery of data.
- 🧠 **Example**: Downloading files using `TCP`, streaming with `UDP`.
- 🎯 **Use Case**: Web traffic, file transfer, video streaming.
- ⚡ **Tips**: `TCP` = reliable with acknowledgments, `UDP` = fast with no checks.

---

## 4️⃣ Application Layer (Combines OSI Layers 5-7)

- ✅ **Description**: Provides applications with access to network services.
- 🧠 **Example**: Using a browser with `HTTP`, email with `SMTP`.
- 🎯 **Use Case**: Web, email, FTP, remote access, DNS.
- ⚡ **Tips**: Protocols: `HTTP`, `DNS`, `SSH`, `FTP`, `SMTP`

---

# 🔁 TCP/IP vs OSI Model — Side-by-Side Comparison

| Feature         | OSI Model (7 Layers)                  | TCP/IP Model (4 Layers)            |
|----------------|----------------------------------------|------------------------------------|
| Purpose         | Educational, detailed                 | Practical, real-world use          |
| Layers          | Application → Physical (7 layers)     | Application → Network Access (4)  |
| Complexity      | More granular                         | More simplified                    |
| Used by         | Mostly academic/troubleshooting       | Used in real internet operations   |

---

# 🧠 Final Takeaways

- TCP/IP and OSI are **conceptual frameworks** to understand how computers communicate.
- TCP/IP is **used in practice**, OSI is used for **teaching and troubleshooting**.
- Knowing these models helps security professionals **identify where problems or threats occur**.

---
# 🌐 Ultimate Guide to Network Protocols for Cybersecurity Analysts

> ✍️ Authored from the Google Cybersecurity Professional Certificate curriculum.  
> 🛡️ Best suited for entry-level cybersecurity professionals and tech enthusiasts.

---

## 📌 What Are Network Protocols?

**Network protocols** are standardized rules that define how data is formatted, transmitted, and received over a network. Think of them as the grammar rules of the internet — without them, devices couldn’t understand each other.

📦 Every piece of data sent over the internet is wrapped in a **data packet**. Protocols tell devices:
- What to do with the packet 📬
- How to interpret the data 🧠
- When and where to send it 🚦

> 🔐 **Security Perspective**: Protocols can be exploited. A strong grasp of them helps cybersecurity professionals detect, defend, and mitigate attacks.

---

## 🧭 3 Main Categories of Protocols

| Category     | Description                                         | Why It Matters in Cybersecurity 🔍 |
|--------------|-----------------------------------------------------|------------------------------------|
| Communication| Moves data between devices                          | Analyze how attackers send data    |
| Management   | Monitors and manages network devices                | Detect configuration issues        |
| Security     | Secures data with encryption                        | Prevent eavesdropping and tampering|

---

# 📡 Communication Protocols

These protocols govern **how data is sent, received, and structured** during transit.

---

## 🔁 Transmission Control Protocol (TCP)

- ✅ **What It Is**: A **connection-oriented** protocol ensuring data reaches the destination **reliably and in order**.
- 📶 **3-Way Handshake**:
  1. SYN →
  2. SYN-ACK ←
  3. ACK →
- 🧠 **Example**: Browsing Gmail or downloading software.
- 🎯 **Use Case**: Any task where **data accuracy** matters.
- ⚡ **Tip**: Use TCP for file transfers, emails, and websites.

```txt
Layer: Transport
Ports: Varies (based on application)
Reliable: ✅ Yes
```

---

## 🛰️ User Datagram Protocol (UDP)

- ✅ **What It Is**: A **connectionless**, fast protocol. It doesn't check if packets arrive — just sends them!
- 🧠 **Example**: Streaming YouTube, Online Games, DNS queries.
- 🎯 **Use Case**: Real-time tasks where speed > perfection.
- ⚡ **Tip**: Use when dropped packets are tolerable.

```txt
Layer: Transport
Ports: Varies (e.g., 53 for DNS)
Reliable: ❌ No
```

---

## 🌐 Hypertext Transfer Protocol (HTTP)

- ✅ **What It Is**: Protocol used by web browsers to communicate with servers.
- 🧠 **Example**: Accessing `http://example.com`
- 🎯 **Use Case**: Viewing websites, APIs.
- ⚠️ **Security Risk**: Sends data in plain text!
- ⚡ **Tip**: Avoid entering passwords on HTTP sites.

```txt
Layer: Application
Port: 80
Security: ❌ Insecure
```

---

## 🧭 Domain Name System (DNS)

- ✅ **What It Is**: Translates domain names like `google.com` into IP addresses.
- 🧠 **Example**: Typing a URL and loading a site.
- 🎯 **Use Case**: Resolving any hostname to IP.
- ⚠️ **Risk**: DNS Spoofing can redirect users to fake websites.
- ⚡ **Tip**: DNS uses UDP, switches to TCP if needed.

```txt
Layer: Application
Ports: 53 (UDP, falls back to TCP)
Security: ⚠️ Vulnerable to spoofing
```

---

# ⚙️ Management Protocols

Used to **monitor, report, and manage** network health.

---

## 🛠️ Simple Network Management Protocol (SNMP)

- ✅ **What It Is**: Helps admins monitor network devices.
- 🧠 **Example**: Check router bandwidth usage.
- 🎯 **Use Case**: Automated alerts, device configurations.
- ⚠️ **Risk**: Weak SNMP versions can leak config data.
- ⚡ **Tip**: Use SNMPv3 — it includes encryption.

```txt
Layer: Application
Port: 161 (UDP)
Security: V1 & V2c = ❌, V3 = ✅
```

---

## 📶 Internet Control Message Protocol (ICMP)

- ✅ **What It Is**: Sends messages about packet delivery failures.
- 🧠 **Example**: `ping google.com` to test reachability.
- 🎯 **Use Case**: Network diagnostics & troubleshooting.
- ⚠️ **Risk**: Ping floods can overwhelm devices (DoS attack).
- ⚡ **Tip**: Disable ICMP on public-facing devices if not needed.

```txt
Layer: Internet
Port: N/A (protocol number 1)
Security: ⚠️ Can be abused for scanning
```

---

# 🔐 Security Protocols

These protect **confidentiality, integrity, and authenticity** of network data.

---

## 🔒 Hypertext Transfer Protocol Secure (HTTPS)

- ✅ **What It Is**: Secure version of HTTP using **SSL/TLS**.
- 🧠 **Example**: Online shopping, banking.
- 🎯 **Use Case**: Any web-based app that needs encryption.
- ⚡ **Tip**: Use HTTPS **everywhere**, especially with sensitive data.

```txt
Layer: Application
Port: 443
Encryption: ✅ SSL/TLS
```

---

## 📁 Secure File Transfer Protocol (SFTP)

- ✅ **What It Is**: Secure file transfer using SSH.
- 🧠 **Example**: Uploading data to cloud from terminal.
- 🎯 **Use Case**: Secure backups, cloud sync.
- ⚡ **Tip**: Use SFTP over FTP to prevent credential theft.

```txt
Layer: Application
Port: 22 (via SSH)
Encryption: ✅ AES (via SSH)
```

---

> 🔍 **Remember**: These protocols encrypt content, but not IP addresses! Attackers can still perform **traffic analysis**.

---

## ✅ Summary Table

| Protocol | Type | Layer | Port | Secure? | Common Use |
|---------|------|-------|------|--------|------------|
| TCP     | Comm | Transport | Dynamic | ✅ | Reliable transmission |
| UDP     | Comm | Transport | Dynamic | ❌ | Fast, real-time |
| HTTP    | Comm | Application | 80 | ❌ | Websites |
| DNS     | Comm | Application | 53 | ⚠️ | URL to IP resolution |
| SNMP    | Mgmt | Application | 161 | ⚠️ | Network monitoring |
| ICMP    | Mgmt | Internet | N/A | ⚠️ | Diagnostics (ping) |
| HTTPS   | Sec  | Application | 443 | ✅ | Secure websites |
| SFTP    | Sec  | Application | 22 | ✅ | Secure file transfer |

---

## 🧠 Final Takeaways for Cybersecurity Analysts

- Learn how each protocol **works AND can be exploited**.
- Recognize signs of **protocol abuse** (e.g., DNS tunneling, ICMP exfiltration).
- Secure communication using **modern encryption protocols**.
- Use tools like **Wireshark, tcpdump**, and **nmap** to explore real traffic.

---

🔐 **Stay sharp. Secure smart.**  
📚 *These notes will evolve as your cybersecurity journey progresses.*

---

© 2025 | Maintained by [Tirthak Likhar](https://www.linkedin.com/in/tirthak-likhar-8808a8255/)

> ✨ This cheat sheet is part of a beginner-friendly cybersecurity knowledge base. Fork, star, and contribute to make it better!


