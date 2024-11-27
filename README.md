# Globally Distributed Load Balancer Design

## Project Overview
This project focuses on designing a **secure and globally distributed application architecture** for **Tyrell Crop**. The solution addresses the organization’s requirement to serve both static image content and dynamically rendered web pages with minimal latency to a global user base.

---

## Key Features
- **Low Latency Delivery**: Traffic is routed to the nearest region, ensuring quick and seamless content delivery.
- **Traffic Segmentation**: Separate infrastructure for `/images/*` URLs and other web pages.
- **Secure and Scalable**: Incorporates Azure services to maintain security and scalability.

---

## Objectives
### **What I Did**:
- Designed and deployed a **Load Balancing architecture** using **Azure Traffic Manager**, **Application Gateways**, and **Virtual Networks**.
- Segmented static image content and dynamic web content onto distinct virtual machines for efficient resource usage.

### **How It Helped**:
- Delivered a reliable, geographically redundant system with optimized latency for users worldwide.
- Secured the environment by implementing **Azure Network Security Groups (NSGs)**.

### **Benefits to the Organization**:
- Enhanced user satisfaction with fast and consistent access to services.
- Built a scalable architecture ready for future expansion across additional regions.

---

## Resources Used
1. **Azure Virtual Networks**  
2. **Azure Virtual Machines**  
3. **Azure Network Security Groups (NSGs)**  
4. **Azure Network Interface Cards (NICs)**  
5. **Azure Application Gateway**  
6. **Azure Traffic Manager**  
7. **Availability Sets**

---

## Deployment Steps
1. **Create Virtual Networks** in the East US region and an additional region of your choice.
2. Deploy **Virtual Machines**:
   - One pool for serving static image content (`/images/*` URLs).
   - Another pool for dynamic web pages.
3. Set up **Application Gateways** for routing traffic within each region.
4. Connect the regions using **Azure Traffic Manager** for global load balancing.
5. Configure **Network Security Groups (NSGs)** to secure all traffic between resources.
6. Validate the setup by testing traffic routing, latency, and security compliance.

---

## Future Enhancements
- Expand the architecture to include additional global regions for broader coverage.
- Implement **Auto-Scaling** for managing dynamic traffic loads.
- Explore using **Azure Front Door** for advanced content delivery capabilities.

---

This project showcases a real-world scenario of implementing a robust, secure, and highly available architecture using **Azure Cloud Services**. It reflects the ability to solve complex business problems through cloud-based solutions effectively.

---

## Contact
For questions or contributions:  
Akash Majumdar(https://github.com/search4akash)  
Mail: search4akash@outlook.com
