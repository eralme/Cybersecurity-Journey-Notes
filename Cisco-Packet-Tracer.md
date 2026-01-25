# Cisco Packet Tracer

## Installation
- Refer to official documentation for setup instructions.

## Hubs
- **Layer:** OSI Layer 1 (Physical).
- **Topology:** Star topology.
- **Function:** Broadcasts incoming packets to all ports; every connected device receives the data.
- **Simulation Steps:**
  1. Add a Hub and multiple PCs to the workspace.
  2. Connect devices using **Ethernet straight-through** cables.
  3. Assign IP addresses to each PC.
  4. Verify connectivity using the `ping` command.
  5. Use **Simulation Mode** to observe broadcasting behavior.
- **Pros:**
  - Inexpensive.
  - Simple for small networks.
- **Cons:**
  - **Network Flooding:** Excessive broadcasting impacts performance.
  - **No Memory:** Does not store MAC addresses or device info.
  - **Half-Duplex:** Cannot send and receive data simultaneously.
  - **Legacy:** Mostly replaced by modern switches.

---

## Switch
- **Layer:** OSI Layer 2 (Data Link).
- **Topology:** Star topology.
- **Function:** Connects devices on a network to establish a LAN. Stores MAC address table and forwards data only to the intended destination.
- **Simulation Steps:**
  1. Add a Cisco 2960 Switch and multiple PCs to the workspace.
  2. Connect devices using **Ethernet straight-through** cables.
  3. Assign IP addresses to each PC.
  4. Verify connectivity using the `ping` command.
  5. Use **Simulation Mode** to observe unicast behavior.
- **Pros:**
  - Intelligent data forwarding (unicast, multicast, broadcast as needed).
  - Stores MAC address tables.
  - Full-duplex mode (send and receive simultaneously).
  - More efficient and secure than hubs.
- **Cons:**
  - More expensive than hubs.
  - More complex configuration.

---

## Hub vs. Switch Comparison

| Feature | Hub | Switch |
|---------|-----|--------|
| **OSI Layer** | Layer 1 (Physical) | Layer 2 (Data Link) |
| **Memory** | Has no memory | Has memory, stores MAC Address Table |
| **Intelligence** | Not an intelligent device | Intelligent device |
| **Network Behavior** | Floods the network due to broadcasting | Can do unicasting, multicasting, and broadcasting |
| **Security Risk** | Security risks are high | Security risks are low |
| **Efficiency** | Less efficient | More efficient |
| **Duplex Mode** | Half Duplex | Full Duplex |
