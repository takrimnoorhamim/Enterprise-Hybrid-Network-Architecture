# Enterprise Hybrid Network Architecture Design

## 📌 Project Overview
This project demonstrates the design of a physical hybrid network architecture for an enterprise with three separate branches. The objective is to integrate multiple topologies, establish WAN interconnection, and implement basic network security placement (firewalls and server zoning) using draw.io.

## 🏢 Network Topologies Implemented
Each branch operates on a specific hybrid topology tailored to its operational needs:

* **Branch A (Tree Topology):** A combination of Star and Bus topologies, utilizing a main switch connected to the branch router.
* **Branch B (Hybrid Mesh & Star):** Features a robust combination of Mesh and Star topologies for high redundancy.
* **Branch C (Hybrid Bus & Ring):** Integrates Bus and Ring topologies for structured data flow.

## 🔒 Security & Connectivity Features
* **WAN Interconnection:** All three branch routers are connected via a centralized WAN cloud.
* **Security Placement:** Strategic placement of firewalls between the internal network and external WAN.
* **Network Segmentation:** Clear separation of internal wired networks, secure server zones (placed behind firewalls), and wireless access points.

## 🛠️ Tools Used
* **draw.io:** For network diagramming and physical architecture mapping.