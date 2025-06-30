# Capture-and-Analyse-Network-Traffic

---

## 🧰 Tools Used
- **Operating System**: Kali Linux
- **Capture Tools**: Wireshark / tcpdump
- **File Format**: `.pcap` (Packet Capture format)

---

## 🛠️ Steps Performed

### 1. Identify Active Network Interface
```bash
ip route
```

### 2. Start Packet Capture

Using Wireshark:
	•	Open Wireshark: 
```bash
wireshark &
```

### 3. Generate Network Traffic
Open a browser or terminal:
 ```bash
ping google.com
```
Or browse to https://example.com


### 4. Stop the Capture
	•	In Wireshark: Click the red stop button
	•	In tcpdump: Press Ctrl + C

### 5. Analyze Captured Traffic

Use Wireshark filters like:
	•	http (web traffic)
	•	dns (domain resolution)
	•	tcp (transport layer)
	•	icmp (ping)

### 6. Identify Protocols

Common protocols observed:
	•	TCP
	•	DNS
	•	HTTP/HTTPS
	•	ICMP

### 7. Export the Capture
File saved as: ElevateLabs.pcap
In Wireshark: File > Save As > ElevateLabs.pcap
