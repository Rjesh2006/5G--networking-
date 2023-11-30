# [5G master class module:-]()👇

# The 5G System summary 


## Standardization of 5G
Ensuring global compatibility is a critical aspect of the 5G system. The International Telecommunication Union (ITU) is at the forefront of standardization efforts. ITU-T, responsible for telecommunication standards, ensures that 5G technologies adhere to globally accepted specifications. ITU-R focuses on wireless communication, emphasizing the need for seamless connectivity across diverse environments. Additionally, ITU-D plays a crucial role in telecommunication development, fostering inclusivity and accessibility worldwide.

## 3GPP (3rd Generation Partnership Project)
The collaborative efforts within the 3rd Generation Partnership Project (3GPP) bring together a diverse array of international telecommunication organizations and private companies. This collective initiative aims to implement technologies specified by the ITU, ensuring that 5G is a result of global collaboration. Technical Specification Groups (TSG) within 3GPP, such as TSG RAN for wireless communication, TSG CT for mobility and security, and TSG SA for multimedia codecs, provide a structured framework for the development and implementation of 5G standards.

## Use Cases of 5G
### Enhanced Mobile Broadband (eMBB)
Enhanced Mobile Broadband (eMBB) is a pivotal use case for 5G, emphasizing the delivery of significantly higher data rates, increased network capacity, and an overall enhancement of user experiences. This use case enables applications such as ultra-high-definition video streaming, augmented reality, and virtual reality, driving the evolution of multimedia experiences.


### Massive Machine Type Communication (mMTC)
Massive Machine Type Communication (mMTC) addresses the connectivity needs of the Internet of Things (IoT). This use case is designed to support a vast number of simultaneous connections, providing optimized energy efficiency to accommodate the diverse array of IoT devices. mMTC lays the foundation for a seamlessly connected and interoperable IoT ecosystem.


### Ultra-Reliable Low Latency Communication (URLLC)
Ultra-Reliable Low Latency Communication (URLLC) caters to applications demanding extremely low latency and high reliability. This includes mission-critical services such as autonomous vehicles, remote surgery, and industrial automation. URLLC ensures that 5G networks can meet the stringent requirements of real-time, high-reliability applications.


## The 5G System Components
### User Plane Function (UPF)
The User Plane Function (UPF) is a cornerstone of the 5G system, serving multifaceted roles. Acting as a mobility anchor, UPF ensures seamless handovers between different network nodes. Furthermore, it enforces policies, regulating the flow of data in alignment with network and service requirements. UPF also facilitates lawful interception, contributing to the security framework of the 5G network.

### Session Management Function (SMF)
The Session Management Function (SMF) plays a central role in 5G network architecture by managing session-related messages. Collaborating closely with the Access and Mobility Function (AMF), SMF oversees the establishment, modification, and termination of sessions. This includes ensuring the continuity of communication during handovers and adapting to dynamic network conditions.


### Authentication Server Function (AUSF)
The Authentication Server Function (AUSF) is a key component in ensuring the security of the 5G network. AUSF supports the AMF by providing authentication services, verifying the identity of users and devices. This contributes to the overall integrity and confidentiality of communications within the 5G ecosystem.

### User Data Management (UDM)
User Data Management (UDM) serves as the front end for User Subscription Data (USR) within the 5G network. It holds vital user-related information and provides necessary data to the AMF when required. UDM ensures efficient access to user profiles, contributing to personalized and secure services within the 5G landscape.


### Policy Control Function (PCF)
The Policy Control Function (PCF) is a critical component supporting various functions within the 5G system. It plays a pivotal role in charging-related functions, providing policies for both session management and scenarios where no session is established. PCF contributes to the efficient utilization of network resources, ensuring a balance between service quality and resource optimization.


## Visual Representations
The provided images offer detailed visual representations of the 5G system, showcasing network architecture, control and user planes, and the interplay of various components. These visuals provide an in-depth understanding of the intricate details of the 5G ecosystem, aiding in comprehensive system comprehension and analysis.



# 5G Deployment Options

## Overview
- **EPC (Evolved Packet Core):** Key component in 5G deployment.
- Currently reliant on 4G LTE (eNodeB) for voice calls and 5G (gNodeB) for internet access.
- Various modification options exist for optimizing the system.

## Options
### Option 3
- Core network sends data to eNodeB, splitting it between UE and gNodeB.
- eNodeB sends data at smaller rates, while gNodeB sends it at a higher rate.


#### Option 3a
- Direct data transfer from core network to gNodeB at a higher rate, but with disadvantages for voice calls.


#### Option 3x
- Combination of options 3 and 3a, with communication between eNB and gNB and data sent to UE.


### Option 6
- Not officially supported.


## Stand Alone and Non-Stand Alone
- Different deployment options categorized into Stand Alone (Option 1, 2) and Non-Stand Alone (Option 3, 4, 7).

# 5G NR (New Radio)

## RAN Protocol Stack

- Two types: UPPS (user data) and CPPS (control information).
- SDAP layer supports quality of service.

### User Plane Protocol Stack

1. **Physical Layer (PHY):** Efficient wireless communication.
2. 
3. **MAC Layer:** Retransmission, multiplexing, scheduling.
4. 
5. **RLC Layer:** ARQ (Automatic Repeat Query) segmentation.
6. 
7. **PDCP Layer:** Header compression, ciphering, integrity protection, duplicate removal.
8. 
9. **SDAP Layer:** Quality of service.
![image](https://github.com/Rjesh2006/5G---For-Everyone-/assets/143868643/008c999d-aad5-4ba6-b763-5c21aaa73cfa)



### Control Plane Protocol Stack

1. **NAS (Non Access Stratum):** Authentication, security, idle mode procedures, IP address assignment.
2. **RRC (Radio Resource Control):** System information, radio bearers, measurement configuration.

## SDAP (Service Data Adaptation Protocol)

- Types of traffic and QoS flows explained.

### Types of Traffic

- Differentiates between Guaranteed Bit Rate (GBR) and Non-GBR QoS flows.

### QoS Flows  

- Additional QoS flows established when triggered by corresponding applications.

### QoS Flow Types

- **GBR:** Guaranteed bit rate QoS flow.
- **Non-GBR:** Used for bursty traffic.
  
- ![image](https://github.com/Rjesh2006/5G--networking-/assets/143868643/ade99346-51e5-4679-8a1d-1e06ce4e91b8)



# 5G QoS Identifiers (5QI)
### Key Points: QoS Identifiers in 5G

- **5QI (5G QoS Identifiers)**: Values from 1 to 79 classify and prioritize data traffic.
  
- **Traffic Prioritization**: Assigns specific QoS profiles to different data types based on their needs.
  
- **Resource Allocation**: Manages network resources (e.g., bandwidth, latency) according to 5QI values.
  
- **Service Quality Differentiation**: Ensures diverse applications receive suitable service levels.
  
- **Dynamic Adaptation**: Adjusts QoS parameters in real-time for changing network conditions.
  
- **End-to-End QoS**: Maintains consistent service quality across the entire 5G network architecture.



# PDCP (Packet Data Convergence Protocol)

 ## Functions of PDCP



- Header compression
- Ciphering and integrity protection
- Routing and duplication of split bearers
- In-sequence delivery


- PDCP performs header compression to reduce header length for wireless transmission.
- Decompression of header size before transmission over IP protocols in the wired network is done by PDCP.
- Header compression scheme is based on Robust Header Compression (ROHC) protocol.


- In case of failure, UE's can receive data from the other bearer.
- PDCP is responsible for discarding duplicates and selecting the packet in the receiving side.


- PDCP acts as a sequence number to ensure in-sequence delivery.

# RLC (Radio Link Control)

 ## Functions of RLC

![image](https://github.com/Rjesh2006/5G---For-Everyone-/assets/143868643/43dc603b-eb7b-44a1-9c2f-6645917cef06)



- Segmentation
- ARQ (Automatic Repeat reQuest) - Retransmissions


- Transparent mode: No need for segmentation and retransmission.
- Unacknowledged mode: Error-free delivery not required.
- Acknowledged mode: Used for web browsing, file transfer, etc.


- Various bit sizes for unacknowledged and acknowledged modes.
- Segmentation retains the same sequence number as unsegmented SDU.



# MAC (Medium Access Control)

## Functions of MAC
![image](https://github.com/Rjesh2006/5G---For-Everyone-/assets/143868643/2923252a-c24a-4272-b382-0af85c66c0e8)


- Logical channel multiplexing
- Hybrid-ARQ retransmissions
- Scheduling
- Multiplexing/demultiplexing for CA
- MAC layer provides services to RLC through logical channels


- Logical channels are defined by the type of information they carry.
- Transport channels are defined by how and what characteristics information is transmitted over.


 ## Logical Channels

- PCCH: Paging of devices with unknown location to the network.
- BCCH: Transport of network information from network to all cells.
- CCCH: Transmission of control information with random access processes.
- DTCH: Transmission of user data to and from devices, handling a significant amount of data traffic.
- DCCH: Transfer of control information to devices.

 ## Transport Channels

- PCH: Transport of paging information from PCCH in logical channels.
- BCH: Transport of BCCH, specifically the master information block.
- DL-SCH: Main transport channel for downlink data in NR.
- UL-SCH: Uplink counterpart of downlink shared channel.


 ## Hybrid-ARQ (HARQ)

- Main mechanism for transmission in 5G, supporting error correction using channel coding and retransmission when error cannot be corrected.
- Each process transmits a data unit and waits for feedback before transmitting the next data unit


# PHY ( physical layer)
 ## function of physical layer
 - The physical layer in a communication system, including 5G (fifth generation), is responsible for the transmission and reception of the raw data bits over the physical medium, such as radio waves in the case of wireless communication. The physical layer defines how the digital bits are converted into analog signals for transmission and how received analog signals are converted back into digital bits.
 - In the context of 5G, the physical layer has several key features and technologies to enable high data rates, low latency, and improved reliability. Some of the key aspects of the physical layer in 5G include
