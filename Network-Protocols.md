## Network Protocols: TCP/IP, HTTP, DNS

### TCP/IP

A suite of protocols governing data transmission over the internet.

**Key functions:**
- Breaks data into packets
- Addresses and routes packets
- Ensures reliable delivery at destination

**Characteristics:**
- Hardware/software agnostic
- Layered architecture
- Foundation of internet communication

### TCP/IP Layered Model

| Layer | Function | Key Protocols |
|-------|----------|---------------|
| Application | Network services to apps | HTTP, HTTPS, SMTP, FTP, DNS |
| Transport | End-to-end data delivery | TCP, UDP |
| Internet | Addressing & routing | IP (IPv4, IPv6) |
| Network Access | Physical transmission | Ethernet, Wi-Fi, PPP |

#### Transport Layer: TCP vs UDP

| Feature | TCP | UDP |
|---------|-----|-----|
| Connection | Connection-oriented | Connectionless |
| Reliability | Guaranteed delivery | Best-effort |
| Ordering | Maintained | Not guaranteed |
| Use Cases | Web, email, file transfer | Streaming, gaming, VoIP |

**TCP 3-Way Handshake:** SYN → SYN-ACK → ACK

#### Internet Layer

- **IP Addressing:** Unique device identifiers (IPv4: 32-bit, IPv6: 128-bit)
- **Routing:** Routers forward packets using routing tables
- **Fragmentation:** Large packets split for transmission, reassembled at destination

#### Network Access Layer

- **MAC Addressing:** Hardware identifier for each NIC
- **Ethernet:** Wired network standard
- **Wi-Fi:** Wireless transmission via radio waves

---

### HTTP & HTTPS

Application layer protocols for web communication. HTTP is stateless (each request is independent).

#### HTTP Methods

| Method | Purpose |
|--------|---------|
| GET | Retrieve data |
| POST | Create/submit data |
| PUT | Replace resource |
| PATCH | Partial update |
| DELETE | Remove resource |

#### Common Status Codes

| Code | Meaning |
|------|---------|
| 200 | OK - Success |
| 301 | Moved Permanently |
| 404 | Not Found |
| 500 | Internal Server Error |

#### HTTP vs HTTPS

| Feature | HTTP | HTTPS |
|---------|------|-------|
| Security | Unencrypted | SSL/TLS encrypted |
| Port | 80 | 443 |
| Use Cases | Non-sensitive content | Sensitive data, transactions |

#### HTTPS Security Components

- **SSL/TLS:** Cryptographic protocols for secure communication
- **Digital Certificates:** Issued by Certificate Authorities (CA) to verify server identity
- **Encryption Process:** Client verifies cert → encrypts with public key → server decrypts with private key
