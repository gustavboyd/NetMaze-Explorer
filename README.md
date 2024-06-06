# NetMaze-Explorer
This project demonstrates the setup of Azure Virtual Networks (VNets), VPN Gateway, and Network Security Groups (NSGs) to establish secure connectivity between on-premises and Azure environments. By following the outlined steps, users can create segregated subnets, simulate on-premises networks, establish VPN connections, deploy resources, and implement network access control.

Azure Services Used:
- Azure Virtual Networks: Create and manage virtual networks to logically isolate Azure resources.
- Azure VPN Gateway: Establish secure VPN connections between Azure VNets and on-premises networks.
- Network Security Groups (NSGs): Control network traffic by defining inbound and outbound security rules.

Steps to Set Up the System:

1. Azure Virtual Network Setup

    1.1 Provision an Azure Virtual Network (VNet) in your chosen region. Create multiple subnets within this VNet to segregate resources effectively (e.g., WebApp Subnet, Database Subnet, Admin Subnet).

2. On-Premises Network Simulation

    2.1 For the sake of this project, use another VNet to simulate your on-premises environment. This can be in another Azure region or the same region based on preference.

3. Secure Connectivity

    3.1 Implement Azure VPN Gateway to create a VPN-to-VPN connection. Verify the connection and ensure resources from one VNet can communicate with another.

4. Resource Deployment

    4.1 Deploy test resources (like VMs) in each subnet of your main Azure VNet. For instance, deploy a web server VM in the WebApp Subnet, a database in the Database Subnet, etc.

5. Network Access Control

    5.1 Use Network Security Groups (NSGs) to define inbound and outbound access rules for each subnet, ensuring that only valid traffic is allowed. For instance, only allow HTTP/HTTPS traffic to the WebApp Subnet.

License:

This project is licensed under the MIT License. See the LICENSE file for more details.

This README provides an overview of setting up Azure Virtual Networks, VPN Gateway, and NSGs for secure network communication in Azure. Follow the outlined steps to establish a segregated network environment with secure connectivity and network access control. For detailed instructions and troubleshooting, please refer to the Azure documentation.
