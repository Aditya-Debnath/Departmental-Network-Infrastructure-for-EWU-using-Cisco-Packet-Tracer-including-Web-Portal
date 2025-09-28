# Departmental-Network-Infrastructure-for-EWU-using-Cisco-Packet-Tracer-including-Web-Portal
Cisco Packet Tracer project designing a secure departmental network for East West University. Includes subnetting, routing (Static and RIP both), FTP with role-based access, email services and web services to ensure full inter-departmental connectivity.

# Departmental Network Infrastructure for East West University

This project is a **network design and implementation** using **Cisco Packet Tracer**, focused on building a secure and scalable **campus-wide infrastructure** for East West University. The design connects multiple departmental LANs and provides communication services such as **FTP**, **Email**, and a **Web Portal** with role-based access control.

---

## 🚀 Project Overview

* **Departments Covered:**

  * CSE
  * EEE
  * Business
  * Law
  * Civil
  * Pharmacy
  * English
  * Genetic Engineering
  * Admin

* **Services Implemented:**

  * **FTP Server**

    * Chairman/Admin PCs: Full Access (Read, Write, Delete, Rename, List)
    * Department PCs: Limited Access (Download, List)
  * **Email Server** for inter-departmental communication
  * **Web Portal (Website)** for academic and administrative info, notices, and announcements
  * **Routing** with Static or Dynamic methods (RIP/OSPF)
  * **Subnetting** with unique IP ranges for each department

---

## 🛠️ Tools & Requirements

* [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)
* Basic knowledge of **Networking, IP addressing, and Routing**
* HTML & CSS (for Web Portal customization)

---

## 📌 Features

* Fully connected university network across all departments
* Secure FTP access based on roles
* Email communication enabled for all PCs
* Web Portal with departmental info and announcements
* Efficient routing with proper segmentation
* Expandable and easy to troubleshoot with subnetting

---

## 🔧 Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/departmental-network-ewu.git
   cd departmental-network-ewu
   ```

2. Open the `.pkt` file in **Cisco Packet Tracer**.

3. Configure IP addresses for each department as per the IP addressing scheme.

4. Set up:

   * **FTP Server** with proper access controls
   * **Email Server** with valid domain setup
   * **Web Server** with HTML/CSS files for the portal (linked via DNS)
   * **Routers** with either Static Routing or RIP/OSPF

5. Test connectivity using `ping`, FTP commands, email exchange, and accessing the website from any PC browser.

---

## 📊 Example IP Addressing Scheme

| Department          | Subnet          |
| ------------------- | --------------- |
| CSE                 | 192.168.10.0/24 |
| EEE                 | 192.168.11.0/24 |
| Business            | 192.168.12.0/24 |
| Law                 | 192.168.13.0/24 |
| Civil               | 192.168.14.0/24 |
| Pharmacy            | 192.168.15.0/24 |
| English             | 192.168.16.0/24 |
| Genetic Engineering | 192.168.17.0/24 |
| Admin               | 192.168.20.0/24 |

---

## 🎯 Expected Outcome

* End-to-end connectivity across departments
* Secure FTP with role-based access
* Functional email service among all PCs
* Fully accessible Web Portal (university website)
* Properly segmented and routed university network

---

## 📖 License

This project is for **academic purposes** under East West University’s CSE Course (CSE405).
