## 🌐 TCP/IP & OSI Model Diagrams

This section breaks down the essential networking models used to understand how data moves through devices, apps, and the internet. Both the OSI and TCP/IP models are visualized, explained in plain English, and applied to real-life IT support cases.

---

### 🧩 Definitions

**OSI Model (Open Systems Interconnection)**: A 7-layer framework that standardizes communication functions in a network.

**TCP/IP Model**: A 4-layer model (sometimes shown as 5) used practically in real-world networking and the internet.

---

### 💡 Explanation (Layman's Terms)

- **OSI**: Think of it like a mail delivery service. Each layer is a different department—writing, sealing, transporting, delivering, etc.
- **TCP/IP**: The real-world version—what actually happens when data travels over the internet.

---

### 🧱 OSI Layers (Top to Bottom)

| Layer | Name             | Role                                       | Example in Action                     |
|-------|------------------|--------------------------------------------|----------------------------------------|
| 7     | Application       | What the user sees                         | Web browser, Email app                 |
| 6     | Presentation      | Formats data (encryption, compression)     | SSL/TLS encryption                     |
| 5     | Session           | Manages connection sessions                | Login tokens, SSH, API sessions        |
| 4     | Transport         | Ensures data delivery (TCP/UDP)            | TCP handshakes, packet acknowledgments |
| 3     | Network           | Determines path (IP addressing/routing)    | Routers, IP addresses                  |
| 2     | Data Link         | MAC addressing, frame creation             | Switches, Ethernet                     |
| 1     | Physical          | Physical medium (wires, signals)           | Cables, Wi-Fi, NICs                    |

---

### 🔀 TCP/IP Model Layers

| Layer        | OSI Equivalent Layers     | Purpose                          |
|--------------|---------------------------|----------------------------------|
| Application  | 7, 6, 5                   | Apps, encryption, sessions       |
| Transport    | 4                         | TCP/UDP handling                 |
| Internet     | 3                         | IP addressing and routing        |
| Network Access | 2, 1                    | Data link and physical hardware  |

---

### 🔄 Real-World Use Cases & Fixes

#### Scenario: Website not loading
- **Layer 1–2 Check**: Network cable unplugged or Wi-Fi down
- **Layer 3 Check**: IP conflict or misconfigured gateway
- **Layer 4 Check**: Firewall blocking port 443 (HTTPS)
- **Layer 7 Check**: Browser misconfigured, DNS issue

#### Scenario: Video lags on Zoom
- **Layer 4**: UDP packet loss due to bandwidth saturation
- **Layer 3**: High latency between your ISP and server
- **Fix**: Prioritize traffic via QoS or switch to wired

---

### 🖼 Diagram: OSI vs TCP/IP

