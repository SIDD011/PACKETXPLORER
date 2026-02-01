# PacketXplorer 🔍  

## 🌐 Network Traffic Analysis Using Wireshark

PacketXplorer is a hands-on cybersecurity project focused on capturing, filtering, and analyzing live network traffic using Wireshark. The project demonstrates practical understanding of modern network protocols, encrypted communications, and basic threat-hunting techniques.

---

## 🎯 Project Objective

- Capture live network traffic
- Apply protocol-based display filters
- Analyze encrypted and unencrypted traffic
- Identify normal network behavior
- Perform basic threat analysis
- Document findings using screenshots and packet capture files

---

## 🛠 Tools & Technology

- Wireshark (Network Protocol Analyzer)
- Windows Operating System
- Command Prompt (ping command)

---

## 🔎 Protocols Analyzed

The following Wireshark display filters were used:

- **icmp** – Ping request and reply packets  
- **dns** – Domain name resolution queries and responses  
- **tcp** – Connection establishment and termination (SYN, ACK, FIN, RST)  
- **tls** – Encrypted HTTPS traffic (TLSv1.2 / TLSv1.3)  
- **quic** – UDP-based encrypted web traffic  

---

## 📂 Project Structure


---

## 📸 Screenshots

The screenshots folder contains visual proof of:

- ICMP Echo Request / Reply
- DNS Query & Response
- TCP Three-Way Handshake
- TLS Encrypted HTTPS Traffic
- QUIC Protocol Traffic

These screenshots support the analysis performed in the capture file.

---

## 🧪 Threat Analysis

- No malicious or suspicious traffic detected  
- DNS queries resolved to legitimate domains  
- Traffic mainly consisted of encrypted HTTPS and QUIC communications  
- No cleartext credentials observed  
- No abnormal port usage detected  
- TCP reset packets observed were normal session behavior  

---

## 📄 Capture File Usage

The capture file is provided in **PCAPNG** format.

### To open the file:
1. Download `network_capture.pcapng`
2. Open Wireshark  
3. Go to **File → Open**  
4. Select the capture file  

> Note: PCAPNG is a binary file format. Opening it in a text editor will display unreadable characters.

---

## 📚 Learning Outcomes

- Packet capturing and filtering skills  
- Understanding of encrypted protocols (TLS & QUIC)  
- Network troubleshooting fundamentals  
- Basic threat-hunting and traffic inspection  
- Hands-on experience with Wireshark  

---

## 🏁 Conclusion

PacketXplorer demonstrates practical network traffic analysis using Wireshark and highlights foundational skills required for SOC Analyst, Blue Team, and Cybersecurity Analyst roles.

---

## 👤 Author

**Siddhesh Patil**  
Cybersecurity & Networking Enthusiast


