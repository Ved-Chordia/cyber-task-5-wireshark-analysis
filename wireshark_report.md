
# Wireshark Packet Capture Report – Task 5

## Objective
Capture live packets using Wireshark and analyze at least three network protocols.

---

## Tool Used
- **Wireshark** (Free & Open Source Packet Analyzer)

---

## Protocols Observed

### 1. HTTP (Hypertext Transfer Protocol)
- **Purpose:** Handles web traffic and browser-based communication.
- **Observation:** Multiple HTTP GET requests were seen for web pages and resources.
- **Insight:** Allows you to see what websites are being accessed in plain text if HTTPS is not used.

### 2. DNS (Domain Name System)
- **Purpose:** Resolves domain names (like google.com) into IP addresses.
- **Observation:** DNS queries were captured every time a new website was opened.
- **Insight:** You can see what domains your device is trying to access — even over HTTPS.

### 3. TCP (Transmission Control Protocol)
- **Purpose:** Ensures reliable communication between client and server.
- **Observation:** Used in almost all data transfers, including HTTP and DNS.
- **Insight:** You can track connection establishment (SYN, ACK) and teardown (FIN).

---

## File Description

- `capture.pcapng`: Exported Wireshark capture file containing live packet data.
- Filters used: `http`, `dns`, `tcp`

---

## What I Learned

- How to start and stop a packet capture in Wireshark
- How to apply filters to isolate specific protocols
- How to identify basic behaviors from network traffic
