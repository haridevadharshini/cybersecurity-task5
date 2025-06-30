# Task 5: Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark on Windows.

---

## 🛠️ Tools Used
- **Wireshark** (Latest version)
- **Windows 11** (host machine)
- **Command Prompt / Web browser** (to generate traffic)

---

## 📌 Steps Performed

1. **Installed Wireshark** from [https://www.wireshark.org/](https://www.wireshark.org/).
2. **Started live capture** on active network interface (Wi-Fi).
3. **Generated traffic**:
   - Opened a browser and visited `https://example.com`
   - Used the command: `ping 8.8.8.8`
4. **Captured for ~1 minute**, then stopped the capture.
5. **Saved the capture file** as `test.pcapng`
6. **Applied filters** to analyze protocols:
   - `icmp` (ping)
   - `dns` (domain lookup)
   - `http` (web traffic)

---

## 🔍 Protocols Identified

| Protocol | Description | Example Packet Details |
|----------|-------------|-------------------------|
| **ICMP** | Internet Control Message Protocol used for `ping` commands | Echo Request/Reply to `8.8.8.8` |
| **DNS**  | Domain Name System resolves domains like `example.com` | Standard query for `example.com` |
| **HTTP** | Web traffic using HyperText Transfer Protocol | GET request to example.com |

---

## 📸 Screenshots
Screenshots of filtered packet views for each protocol (attach or embed in report/presentation):
- `icmp` traffic
- `dns` queries
- `http` GET request

---

## 📁 Files Included
- `test.pcapng`: The Wireshark capture file
- `screenshots/`: Folder containing protocol screenshots (ICMP, DNS, HTTP)

---

## 🧠 Summary
This task demonstrated:
- Real-time packet capturing
- Protocol filtering using Wireshark
- Recognition of core protocols like ICMP, DNS, and HTTP

> 🔐 Wireshark is a powerful tool to visualize and troubleshoot network traffic, which helps understand how different protocols operate on the network layer.

---

## ✅ Outcome
Gained practical experience with:
- Packet analysis
- Filtering protocols
- Identifying common traffic types in a network

