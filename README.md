Designed and implemented a secure network infrastructure using Cisco Packet Tracer, including VLANs, DHCP, DNS, and routing configurations. Focused on network security, segmentation, and efficient communication between departments in a simulated enterprise environment.

Network Overview -

The network is divided into multiple departments such as Sales, HR, and IT. Each department operates within its own Virtual LAN (VLAN), ensuring logical separation and improved network management.


<img width="1893" height="693" alt="Screenshot 2026-04-16 041340" src="https://github.com/user-attachments/assets/e93c1c70-1dbb-4d07-8d45-f5c69e936583" />


Key Configurations

VLAN (Virtual Local Area Network)
VLANs are configured to segment the network into different departments. This reduces broadcast traffic and enhances security by isolating each department.

DHCP (Dynamic Host Configuration Protocol)
A DHCP server is implemented to automatically assign IP addresses to devices, reducing manual configuration and minimizing errors.

DNS (Domain Name System)
DNS is used to resolve domain names into IP addresses, allowing users to access services using human-readable names.

Routing
Inter-VLAN routing is configured using a router to enable communication between different VLANs while maintaining controlled access.

Security Implementation

Security is achieved through VLAN-based network segmentation, controlled communication between departments, and logical isolation to prevent unauthorized access. These measures help protect sensitive data and improve overall network security.

Project Objectives
To design a secure and efficient enterprise network
To implement core networking concepts in a practical environment
To ensure reliable communication between departments
Conclusion

This project demonstrates practical knowledge of networking concepts such as VLANs, DHCP, DNS, and routing. It also reflects an understanding of network security and real-world infrastructure design using Cisco Packet Tracer.

## How to Run the Project

### 1. Open the Project
Open the `.pkt` file in Cisco Packet Tracer.

### 2. Allow Network Initialization
Wait for approximately 5–10 seconds until all device connection indicators turn green and the network becomes stable.

### 3. Verify Network Connectivity
To test communication between VLANs and confirm proper routing configuration:

- Open **PC0**
- Navigate to:
  
Desktop → Command Prompt
Run the following command:
ping 192.168.20.2

Test Server and DNS Configuration

To verify web server and DNS functionality:

Open PC0
Navigate to:
Desktop → Web Browser
Enter the following domain:
mysite.com
Expected Result

If the website loads successfully, it confirms that:

DNS services are functioning correctly
Web server configuration is successful
End-to-end network communication is properly established

# Technologies Used --
Cisco Packet Tracer
VLAN Configuration
Inter-VLAN Routing
DHCP
DNS
Server Configuration
Network Security Concepts
