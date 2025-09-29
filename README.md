# Network-Traffic-Using-Wireshark

# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## 📌 Objective
Capture live network packets on Kali Linux using Wireshark, analyze them, and identify at least 3 different protocols.

---

## 🛠 Tools Used
- **Kali Linux**
- **Wireshark** (for packet capture and analysis)

---

## 🚀 Steps Performed
1. Launched Wireshark using `wireshark &`.
2. Selected the active interface (`wlan0` for Wi-Fi).
3. Started packet capture and generated traffic by:
   - Visiting websites (e.g., https://www.kali.org).
   - Running `ping google.com` in terminal.
4. Stopped capture after ~1 minute.
5. Applied filters (`dns`, `http`, `tcp`, `icmp`) to view specific traffic.
6. Saved capture as **Network Traffic Capture.pcapng**.

---

## 🔎 Protocols Identified
- **DNS (Domain Name System)**  
  Used to resolve domain names into IP addresses. Example: query to `8.8.8.8`.

- **HTTP (HyperText Transfer Protocol)**  
  Used for web requests and responses. Example: HTTP GET request to `www.kali.org`.

- **TCP (Transmission Control Protocol)**  
  Provides reliable, connection-oriented communication.

- **UDP (User Datagram Protocol)**  
  Connectionless protocol used in DNS queries and other lightweight communications.

- **ICMP (Internet Control Message Protocol)**  
  Used for ping (echo request/reply) to test connectivity.

---

## 📂 Files in Repository
- `Network Traffic Capture.pcapng` → Captured packet file.
- `README.md` → Report and explanation of findings.

---

## 📖 Key Learnings
- How to capture live packets using Wireshark.
- How to filter traffic by protocol.
- Difference between TCP, UDP, DNS, HTTP, and ICMP.
- Practical understanding of network troubleshooting using packet captures.
