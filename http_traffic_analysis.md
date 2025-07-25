# HTTP Traffic Analysis using Wireshark

## 🧠 Objective
Capture and analyze real-time HTTP traffic using Wireshark to understand how data is transmitted over the network in plaintext.

---

## 🛠 Tools Used
- *Wireshark*: Packet analyzer used for network troubleshooting and analysis.
- *Kali Linux*: Security-focused OS.
- *Web Browser*: Used to visit an HTTP site (http://example.com).

---

## 🔍 Real-world Scenario
In many real-world attacks, unencrypted HTTP traffic can leak sensitive data like usernames, passwords, session cookies, or internal IP addresses. This lab shows how easy it is to inspect HTTP communication over a network.

---

## 📸 Packet Capture Summary
- Interface used: eth0
- Visited site: http://example.com
- Wireshark captured 6211 packets
- HTTP Response:HTTP/1.1 200 OK Content-Type: text/html Content-Encoding: gzip Connection: keep-alive

---

## 📌 Key Learnings
- HTTP data is visible in plain text.
- Important metadata can be extracted.
- Network forensics requires packet-level visibility.

---

## 🧠 Next Steps
- Analyze POST data in HTTP logins (form submissions)
- Move to HTTPS interception with MITM proxy tools (e.g., mitmproxy)
- Build a capture filter cheat sheet
