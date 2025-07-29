# 🔍 Wireshark – Network Packet Analysis

Wireshark is a network protocol analyzer that lets you inspect what’s happening on your network at a microscopic level.

---

## 🧰 Why Learn Wireshark?
- Visualize network traffic in real-time
- Analyze protocols: TCP, UDP, HTTP, DNS, etc.
- Spot malicious activity or anomalies
- Essential for blue-teamers and threat hunters

---

## 🛠 Basic Usage

### Open a Capture:
- Start Wireshark
- Choose your network interface (usually Wi-Fi or Ethernet)
- Click “Start Capture”

### Filter Traffic:
Examples of display filters:
- ip.addr == 192.168.1.1
- http
- tcp.port == 443
- dns

### Follow a TCP Stream:
Right-click on a packet → Follow → TCP Stream  
This lets you reconstruct conversations between devices.

---

## 🧪 My Practice

| Task | Status |
|------|--------|
| Install Wireshark | ✅ |
| Capture live packets | ✅ |
| Apply filters (DNS, HTTP, IP) | ✅ |
| Follow TCP stream | ✅ |
| Export capture to .pcap | ✅ |

---

## 📚 Learning Source
- TryHackMe Room: [Wireshark](https://tryhackme.com/room/wireshark)
- YouTube: John Hammond, NetworkChuck Wireshark tutorials

---

> 🔒 Wireshark helps me understand how real attacks look on the wire. It's like x-ray vision for networks.
