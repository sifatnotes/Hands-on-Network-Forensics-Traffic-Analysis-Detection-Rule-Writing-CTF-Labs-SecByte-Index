# Hands-on-Network-Forensics-Traffic-Analysis-Detection-Rule-Writing-CTF-Labs-SecByte-Index
A practical catalog of cybersecurity CTF labs covering Network Packet Analysis (Wireshark, Zeek, HTTP/TLS inspection), Detection Signature Engineering (Snort, Suricata, Sigma, YARA), Phishing Analysis, and Business Email Compromise (BEC) investigation.
# Network Forensics, Traffic Analysis & Detection Rule Writing CTF Labs

Welcome to the **Network Forensics, Traffic Analysis & Detection Rule Writing CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on deep network telemetry analysis, email threat triage, and signature engineering—including **Packet Capture Analysis (Wireshark, Zeek, TLS/HTTP)**, **Email Security & Forensics (Phishing, Business Email Compromise)**, and **Detection Rule Writing (Snort, Suricata, Sigma, YARA)**.

---

## Lab Collection Index

### 1. Email Security & Infiltration Investigation
* **Phishing Email Investigation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/phishing-email-investigation](https://learn.secbyte.org/ctf/phishing-email-investigation)  
  *Focus:* Extracting email headers, analyzing SPF/DKIM/DMARC authentication results, inspecting malicious attachments, and tracing phishing origin IPs.

* **Demystifying Business Email Compromise**  
  *Lab Link:* [https://learn.secbyte.org/ctf/demystifying-business-email-compromise](https://learn.secbyte.org/ctf/demystifying-business-email-compromise)  
  *Focus:* Investigating executive impersonation, compromised mailboxes, inbox forwarding rules, malicious OAuth applications, and payroll diversion attacks.

### 2. Network Packet Capture & Traffic Analysis
* **Wireshark Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/wireshark-fundamentals](https://learn.secbyte.org/ctf/wireshark-fundamentals)  
  *Focus:* Mastering Wireshark display filters, inspecting protocol hierarchies, following TCP/UDP streams, and extracting carved file objects from PCAPs.

<Image src="image_agent_tag_7843814988219199395" alt="Wireshark packet diagram displaying protocol encapsulation layers" caption="Wireshark Packet Analysis Diagram" />

---

* **Packet Capture Analysis**  
  *Lab Link:* [https://learn.secbyte.org/ctf/packet-capture-analysis](https://learn.secbyte.org/ctf/packet-capture-analysis)  
  *Focus:* Analyzing full packet captures to detect cleartext credential leaks, port scans, protocol malformations, and anomalous bandwidth spikes.

* **HTTP Traffic Analysis**  
  *Lab Link:* [https://learn.secbyte.org/ctf/http-traffic-analysis](https://learn.secbyte.org/ctf/http-traffic-analysis)  
  *Focus:* Examining HTTP request/response headers, status codes, user-agent anomalies, POST body payloads, and web application attack patterns.

* **TLS Traffic Investigation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/tls-traffic-investigation](https://learn.secbyte.org/ctf/tls-traffic-investigation)  
  *Focus:* Investigating encrypted communication channels, SNI (Server Name Indication) fields, certificate validity, SSL/TLS handshakes, and RSA key decryption.

* **Zeek Network Monitoring**  
  *Lab Link:* [https://learn.secbyte.org/ctf/zeek-network-monitoring](https://learn.secbyte.org/ctf/zeek-network-monitoring)  
  *Focus:* Working with Zeek (formerly Bro) log files (conn.log, http.log, dns.log, ssl.log), authoring custom Zeek scripts, and performing structured network telemetry parsing.

* **Network Traffic Analysis: Uncovering Secrets**  
  *Lab Link:* [https://learn.secbyte.org/ctf/network-traffic-analysis-uncovering-secrets](https://learn.secbyte.org/ctf/network-traffic-analysis-uncovering-secrets)  
  *Focus:* Advanced PCAP investigation to uncover C2 beaconing, covert data exfiltration channels, malware callbacks, and custom protocol abuse.

### 3. Detection Engineering & Rule Authoring
* **Snort Rule Development**  
  *Lab Link:* [https://learn.secbyte.org/ctf/snort-rule-development](https://learn.secbyte.org/ctf/snort-rule-development)  
  *Focus:* Writing custom Snort NIDS signatures, configuring header/option fields, utilizing `content`, `pcre`, and `byte_test` modifiers, and optimizing rule execution speed.

* **Suricata Rule Development**  
  *Lab Link:* [https://learn.secbyte.org/ctf/suricata-rule-development](https://learn.secbyte.org/ctf/suricata-rule-development)  
  *Focus:* Authoring multi-threaded Suricata rules, leveraging application-layer protocol keywords (`http.uri`, `tls.sni`, `dns.query`), and testing signature performance.

* **Sigma Rule Writing**  
  *Lab Link:* [https://learn.secbyte.org/ctf/sigma-rule-writing](https://learn.secbyte.org/ctf/sigma-rule-writing)  
  *Focus:* Authoring platform-agnostic Sigma rules, defining detection selections/conditions, mapping rules to MITRE ATT&CK techniques, and converting rules to SIEM queries.

* **YARA Rule Development**  
  *Lab Link:* [https://learn.secbyte.org/ctf/yara-rule-development](https://learn.secbyte.org/ctf/yara-rule-development)  
  *Focus:* Authoring YARA signatures for file and memory scanning, writing string/hex conditions, utilizing PE modules, and validating rule efficiency against malware samples.

---

## Learning Path

### Path A: Network Telemetry & Email Forensics Analyst
1. **Email Triage:** Start with [Phishing Email Investigation](https://learn.secbyte.org/ctf/phishing-email-investigation) and [Demystifying Business Email Compromise](https://learn.secbyte.org/ctf/demystifying-business-email-compromise).
2. **Packet Analysis Basics:** Inspect PCAPs via [Wireshark Fundamentals](https://learn.secbyte.org/ctf/wireshark-fundamentals), [Packet Capture Analysis](https://learn.secbyte.org/ctf/packet-capture-analysis), and [HTTP Traffic Analysis](https://learn.secbyte.org/ctf/http-traffic-analysis).
3. **Advanced Telemetry:** Deep dive into network logs using [TLS Traffic Investigation](https://learn.secbyte.org/ctf/tls-traffic-investigation), [Zeek Network Monitoring](https://learn.secbyte.org/ctf/zeek-network-monitoring), and [Network Traffic Analysis: Uncovering Secrets](https://learn.secbyte.org/ctf/network-traffic-analysis-uncovering-secrets).

### Path B: Detection Engineer & Rule Author
1. **Network Signature Writing:** Author inline/NIDS rules in [Snort Rule Development](https://learn.secbyte.org/ctf/snort-rule-development) and [Suricata Rule Development](https://learn.secbyte.org/ctf/suricata-rule-development).
2. **Generic & File Rule Writing:** Build host and binary signatures using [Sigma Rule Writing](https://learn.secbyte.org/ctf/sigma-rule-writing) and [YARA Rule Development](https://learn.secbyte.org/ctf/yara-rule-development).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the direct link to open the exercise environment hosted on Learn SecByte.
3. Review scenario requirements, download PCAP files, or analyze log datasets.
4. Filter network traffic, parse raw headers, author NIDS/YARA rules, or investigate email artifacts to capture flags.

---

## Target Audience

* **SOC Analysts & Incident Responders:** Analyze network packet captures, investigate phishing emails, and parse HTTP/TLS log data.
* **Detection Engineers:** Write, tune, and validate Snort, Suricata, Sigma, and YARA rules against real-world threat telemetry.
* **Network Security Engineers:** Monitor network traffic with Zeek and Wireshark to identify C2 channels and data exfiltration.
* **Cybersecurity Students:** Learn hands-on packet inspection, threat hunting, and signature engineering techniques.

---

## Disclaimer

All lab links in this repository lead to official training environments hosted on Learn SecByte. All materials are provided exclusively for authorized security training, defensive engineering, and educational research purposes.
