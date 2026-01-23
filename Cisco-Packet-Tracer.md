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