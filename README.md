# Structured Cabling Architecture — Advanced Operations Base (BOA)

Telecommunications infrastructure design, sizing, and simulation for a multi-building mission-critical military complex consisting of five operational facilities (Command, Logistics, Training, Security Operations Center, and Maintenance/Intelligence).

### Overview
This project delivers the end-to-end physical and logical infrastructure design compliant with ISO/IEC 11801, TIA-568.2-D, and Tier III data center guidelines (TIA-942-B), validated through a network topology modeled in Cisco Packet Tracer.

### Cabling and Distribution Architecture
- Inter-Building Backbone: Redundant OS2 single-mode optical fiber ring (12F and 8F cores) routed through armored underground HDPE conduits, providing failover convergence via RSTP.
- Horizontal Distribution: Category 6A U/FTP copper cabling (10GBASE-T) running from floor-level Intermediate Distribution Frames (IDFs) to the campus Main Distribution Frame (MDF) at the Command Center.
- Core Redundancy: High-throughput 40G optical interconnect between the Primary Data Center and the Disaster Recovery facility (ESOC) for synchronous replication.

### Network Segmentation and Technical Features
- Logical Segmentation: Structured VLAN architecture segregating Tactical, Administrative, Network Management, Training, VoIP (DSCP EF prioritization), Security IoT, and a physically isolated air-gapped domain for intelligence processing (SIGINT).
- Wireless Infrastructure: Wi-Fi 7 (IEEE 802.11be) campus-wide coverage featuring Multi-Link Operation (MLO), WPA3-Enterprise, and ruggedized IP67 outdoor units managed by centralized controllers (WLC).
- Physical and Electromagnetic Protection: Armored cable paths, grounded metallic raceways, Faraday cage shielding for EMP/HEMP mitigation in classified areas, and physical intrusion detection on rack enclosures.

### Simulation and Budgeting
- Logical and physical campus topology validation within Cisco Packet Tracer (routers, L3/L2 switches, servers, and endpoint simulations).
- Detailed project budget including passive cabling components, active network hardware, redundant power systems (online double-conversion UPS), and specialized deployment labor.
