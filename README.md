# CNRoutingAssignment

This repository contains the official Cisco Packet Tracer (.pkt) configuration files submitted for the Computer Networks (CN) Routing Assignment. 

## 🎓 Student Details
* **University:** NSBM Green University
* **Faculty:** Faculty of Computing
* **Student Name:** Thiranja Ranasinghe
* **Student ID:** 39218

---

## 📁 Repository Structure & File Descriptions

This assignment covers basic router setup, static routing implementations, and dynamic routing configurations. The files included in this repository are detailed below:

### 1. Task1_BasicConfig.pkt
* **Description:** Implements the fundamental Cisco IOS configuration on the target router.
* **Key Configurations:**
  * Router hostname modified to `KandyNSBM_[StudentID]`.
  * Secured the console line interface with password authentication (`NSBM`).
  * Enabled terminal login requirements.

### 2. Task2_StaticRouting.pkt
* **Description:** Features a multi-router topology configured using Static Routing.
* **Key Configurations:**
  * Manual IP address allocation across router interfaces and end devices.
  * Implementation of standard static routes (`ip route`) to establish end-to-end connectivity between disjoint subnets.

### 3. Task3_DynamicRouting.pkt
* **Description:** Demonstrates the implementation and behavior of dynamic routing protocols within a complex network topology.
* **Key Configurations:**
  * Routing Information Protocol (RIP) / Enhanced Interior Gateway Routing Protocol (EIGRP) configuration.
  * Network propagation and convergence validation via automated routing tables.

---

## 💻 Software Requirements
* **Application:** Cisco Packet Tracer (v8.2 or higher recommended)
* **How to verify:** Clone or download the files, open them in Packet Tracer, and use the `show running-config` or `show ip route` commands in the CLI to inspect configurations.
