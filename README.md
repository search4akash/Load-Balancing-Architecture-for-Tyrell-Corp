# Globally Distributed Load Balancer Design

## Project Description
This project involves designing a highly secure, globally distributed application architecture for **Tyrell Crop**, addressing their requirement to deliver content with low latency and geographical redundancy. The solution differentiates between static image content and dynamically rendered web pages by using dedicated infrastructure for each.

---

## Features
- **Geographic Redundancy**: Ensures users are served from the nearest (lowest latency) location.
- **Content Segmentation**: Implements a separate pool of virtual machines for image content.
- **Scalable Architecture**: Utilizes Azure Traffic Manager and Application Gateways to handle traffic distribution and redundancy.

---

## Business Scenario
### **What I Did**:
- Designed a **Load Balancing architecture** leveraging **Azure Traffic Manager**, **Application Gateways**, and **Virtual Machines** to deliver dynamic and static content globally.
- Segmented traffic based on URL patterns, optimizing resource allocation for different types of content.

### **How It Helped**:
- Enhanced the user experience by reducing latency through geographically distributed infrastructure.
- Secured application delivery by employing robust **Azure Network Security Groups (NSGs)**.

### **Benefits to the Organization**:
- Improved system reliability and user satisfaction with seamless content delivery.
- Scalable and fault-tolerant architecture prepared for global expansion.

---

## Resources Used
1. **Azure Virtual Networks**  
2. **Azure Virtual Machines**  
3. **Azure Network Security Groups**  
4. **Azure Network Interface Card (NIC)**  
5. **Azure Application Gateway**  
6. **Azure Traffic Manager**  
7. **Availability Sets**

---

## Installation and Usage
### Steps to Deploy:
1. **Create Virtual Networks** in the East US region and another region.
2. Set up **Virtual Machines** for dynamic content and a dedicated pool for static content.
3. Configure **Application Gateways** and associate them with the Traffic Manager profile.
4. Ensure proper **Network Security Groups** to secure the infrastructure.
5. Validate the deployment with end-to-end testing for low latency and security.

---

## Future Enhancements
- Add additional regions to further enhance global reach.
- Implement automated scaling for handling peak traffic loads.
- Explore Azure Front Door for enhanced content delivery.

---

## Contact
For questions or contributions:  
Akash Majudmar
(https://github.com/search4akash)  
search4akash@outlook.com
