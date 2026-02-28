# Enterprise Hybrid Network Architecture Design

## 📌 Project Overview
[cite_start]This project demonstrates the design of a physical hybrid network architecture for an enterprise with three separate branches[cite: 20, 22]. [cite_start]The objective is to integrate multiple topologies, establish WAN interconnection, and implement basic network security placement (firewalls and server zoning) using draw.io[cite: 20, 21].

## 🏢 Network Topologies Implemented
Each branch operates on a specific hybrid topology tailored to its operational needs:

* [cite_start]**Branch A (Tree Topology):** A combination of Star and Bus topologies, utilizing a main switch connected to the branch router[cite: 39, 40, 41].
* [cite_start]**Branch B (Hybrid Mesh & Star):** Features a robust combination of Mesh and Star topologies for high redundancy[cite: 43, 44].
* [cite_start]**Branch C (Hybrid Bus & Ring):** Integrates Bus and Ring topologies for structured data flow[cite: 46, 47].

## 🔒 Security & Connectivity Features
* [cite_start]**WAN Interconnection:** All three branch routers are connected via a centralized WAN cloud[cite: 23, 53].
* [cite_start]**Security Placement:** Strategic placement of firewalls between the internal network and external WAN[cite: 58].
* [cite_start]**Network Segmentation:** Clear separation of internal wired networks, secure server zones (placed behind firewalls), and wireless access points[cite: 59, 60].

## 🛠️ Tools Used
* [cite_start]**draw.io:** For network diagramming and physical architecture mapping[cite: 24].