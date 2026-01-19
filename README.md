# LS170: Networking Foundations

**Repository:** [https://github.com/christinelinster/ls-170](https://github.com/christinelinster/ls-170)

This course explores the fundamental infrastructure that powers the web, moving from the physical characteristics of the internet up to the application layer. The primary focus is on **HTTP** (Hypertext Transfer Protocol)—demystifying the request/response cycle, understanding state, and securing communications via TLS.

## Core Concepts Mastered

### Network Infrastructure
* **Physical Layer:** Understanding how data is physically transferred via fiber optics, copper, and wireless signals (Latency vs. Bandwidth).
* **Conceptual Models:** Mapping network communication to the **OSI 7-Layer Model** and the **TCP/IP Model**.
* **Addressing:** How **IP Addresses** (IPv4/IPv6) locate machines and how **DNS** (Domain Name System) translates human-readable URLs into IP addresses.


### Transport Layer (TCP/UDP)
* **TCP (Transmission Control Protocol):** Connection-oriented communication ensuring reliability through the "Three-Way Handshake," packet ordering, and error-checking.
* **UDP (User Datagram Protocol):** Connectionless, low-latency communication used where speed is prioritized over reliability (e.g., video streaming).
* **Ports & Sockets:** Understanding how endpoints (IP + Port) are established to route traffic to specific applications.

### The HTTP Protocol
* **Request/Response Cycle:** The stateless exchange of messages between client and server.
* **HTTP Verbs:** Semantics of `GET`, `POST`, `PUT`, `DELETE` and their idempotency.
* **Headers:** Metadata exchange for authentication, content negotiation, and caching.
* **State Management:** Overcoming the stateless nature of HTTP using Cookies and Sessions.


### Security
* **TLS (Transport Layer Security):** The evolution of SSL. Encrypting traffic to prevent eavesdropping (Confidentiality).
* **Handshake:** How symmetric and asymmetric encryption are combined to securely exchange keys.
* **Certificates:** The role of Certificate Authorities (CAs) in establishing trust (Authentication).

## Tools & Exercises

Throughout this course, the command line is used to inspect and simulate network traffic:
* **Telnet:** Manually establishing connections to web servers to type raw HTTP requests.
* **Netcat (`nc`):** Creating low-level TCP/UDP connections to listen on ports or send raw data.
* **Wireshark/Packet Tracing:** Visualizing the flow of packets and headers in real-time.

## Key Takeaways
* A mental model of how a URL typed in a browser results in a rendered page.
* Ability to debug network issues using command-line tools.
* Understanding the trade-offs between reliability (TCP) and speed (UDP).
* Knowledge of how modern web security (HTTPS) protects user data.

## License
MIT
