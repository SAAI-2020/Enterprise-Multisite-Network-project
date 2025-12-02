🏢 Enterprise Multi-Site Network Project (Cisco Packet Tracer)

A complete enterprise-grade network designed for a fictional company with an HQ and Branch site.
This project demonstrates professional skills in networking, routing, switching, security, and documentation.

📌 Project Overview

This repository contains a fully configured multi-site enterprise network built using **Cisco Packet Tracer**.

The design includes:

* VLAN segmentation
* Inter-VLAN routing
* DHCP services
* Static routing between sites
* ACL-based firewall rule enforcement
* NAT overload for Internet access
* SSH, Syslog, SNMP configuration
* Port security & STP enhancements
* ISP simulation for default gateway
* Professional documentation + configs

This project is built to showcase **Junior Network Engineer** skills.


📂 Repository Structure

enterprise_network_full/
│
├── README.md
├── documentation/
│   └── full-documentation.md
│
├── configs/
│   ├── hq-router-config.txt
│   ├── branch-router-config.txt
│   ├── hq-switch-config.txt
│   └── branch-switch-config.txt
│
├── diagram/
│   └── network-diagram.png (or .txt placeholder)
│
├── packet-tracer/
│   └── enterprise_network.pkt   (Add your file here)
│
└── guides/
    ├── CONTRIBUTING.md
    └── LICENSE
```

---

## **🧠 Skills Demonstrated**

### **Routing**

* Router-on-a-Stick
* Static Routing HQ ↔ Branch
* WAN Serial Link Configuration

### **Switching**

* VLAN creation
* Access and Trunk ports
* STP (Spanning Tree Protocol)
* Port Security

### **Security**

* Extended ACLs
* SSH with RSA keys
* SNMP monitoring
* Syslog local logging
* NAT overload

### **Services**

* DHCP for all VLANs
* DNS/Internet Simulation
* VLAN-based segmentation

---

## **🌐 Network Topology (High-Level)**

**HQ Site**

* VLAN 10 – HR
* VLAN 20 – IT
* VLAN 30 – Admin

**Branch Site**

* VLAN 40 – Sales
* VLAN 50 – Support

The HQ and Branch are connected using a serial WAN network:

```
HQ Router (10.10.10.1/30) ↔ Branch Router (10.10.10.2/30)
```

---

## **🔐 Access Control Rules (ACL Firewall)**

### IT VLAN (20)

* Block access to HR VLAN
* Allow access to Admin VLAN
* Full access to Branch

### Admin VLAN (30)

* Internet only
* No access to HR/IT

### HR VLAN (10)

* Full access to all networks

---

## **🚀 How to Use This Repository**

### **1. Download the Packet Tracer project**

Open `.pkt` file from the `/packet-tracer` folder.

### **2. Refer to documentation**

Full setup and explanation in:

```
documentation/full-documentation.md
```

### **3. Study device configs**

Router and switch configuration files are under:

```
configs/
```




Just say: **“MAKE DIAGRAM”** or **“RESUME VERSION”**.
