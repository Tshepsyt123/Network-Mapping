# Network Mapping & Connectivity Diagnostic Report
**Course 2: The Bits and Bytes of Computer Networking**

## 1. Introduction
The goal of this project is to map a local network environment and verify the functionality of the TCP/IP stack. By identifying local network parameters and using diagnostic tools like `ping`, I have validated connectivity across the Physical, Network, and Application layers. This report details the logical structure of my connection and provides evidence of successful routing and DNS resolution.

---

## 2. Network Topology Diagram
The following diagram illustrates the path from my local device to the internet.

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/23e10b3a-8f88-4461-b421-6f17e973e78a" />
<img width="588" height="415" alt="ntwk map1" src="https://github.com/user-attachments/assets/e4df4ebf-e9fd-4b38-a61d-77d8e146bc26" />
<img width="595" height="410" alt="ntwk map2" src="https://github.com/user-attachments/assets/9c898c07-6b4c-4a26-b18b-6cb11ea666db" />
<img width="488" height="411" alt="ntwk map3" src="https://github.com/user-attachments/assets/556c6a0b-fb27-490c-b435-af25f63e3423" />

## 5. Conclusion

Based on the results of the network mapping and diagnostic testing, I have reached the following technical conclusions:

* **Addressing:** My device is correctly configured within a **Class B private IP range** (`172.20.x.x`). This indicates the device is part of a private intranet.
* **Subnetting:** The subnet mask `255.255.254.0` confirms a managed network environment. This specific configuration supports up to **510 usable host addresses**, which is significantly larger than a standard home network (typically limited to 254 hosts).
* **Connectivity:** The successful `ping` tests to the default gateway confirm that the **Data Link (Layer 2)** and **Network (Layer 3)** paths are clear and functional. 
* **DNS & Routing:** The successful resolution of `google.com` confirms that the **DNS service (Layer 7)** is correctly translating domain names into routable IP addresses and that the gateway is successfully routing traffic to the Wide Area Network (WAN).

**Final Result:** The network is fully operational and correctly configured for stable and secure communication.




