# Capture and Analyze Network Traffic using Wireshark

## 🎯 Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark.

## 🧰 Tools Used
- Kali Linux (VirtualBox)
- Wireshark
- ping / nslookup / curl commands

## 🧪 Steps Performed
1. Installed Wireshark using `sudo apt install wireshark`.
2. Captured live packets on `eth0` interface.
3. Generated traffic using:
   - `ping -c 4 8.8.8.8`
   - `nslookup google.com`
   - `curl http://example.com`
4. Applied filters:
   - `http`
   - `dns`
   - `icmp`
   - `tcp`
5. Analyzed each protocol and saved results as screenshots.
6. Exported capture as `capture.pcapng`.

## 📊 Protocols Identified
| Protocol | Description | Example |
|-----------|--------------|----------|
| HTTP | Web traffic for websites | GET /index.html |
| DNS | Domain name resolution | Query for google.com |
| ICMP | Ping packets | Echo request/reply |
| TCP | Transport layer protocol | SYN, ACK packets |

## 📸 Screenshots

### 1️⃣ Start Capture on Network Interface
![Start Capture on Interface](screenshots/1_interfaces.png)

### 2️⃣ Live Packet Capture
![Live Packet Capture](screenshots/2_live_capture.png)

### 3️⃣ HTTP Packets (Filtered View)
![HTTP Packets](screenshots/3_http_packets.png)

### 4️⃣ DNS Packets (Filtered View)
![DNS Packets](screenshots/4_dns_packets.png)

### 5️⃣ ICMP Packets (Filtered View)
![ICMP Packets](screenshots/5_icmp_packets.png)

### 6️⃣ TCP Packets (Filtered View)
![TCP Packets](screenshots/6_tcp_packets.png)

## 🧩 Outcome
- Successfully captured and analyzed network traffic.
- Identified multiple common protocols.
- Learned packet inspection and Wireshark filtering.

## 👩‍💻 Author
**Srushti Dave**
