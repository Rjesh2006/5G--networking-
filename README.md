# 5G--networking-
components. These visuals provide an in-depth understanding of the intricate details of the 5G ecosystem, aiding in comprehensive system comprehension and analysis.




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
2. **MAC Layer:** Retransmission, multiplexing, scheduling.
3. **RLC Layer:** ARQ (Automatic Repeat Query) segmentation.
4. **PDCP Layer:** Header compression, ciphering, integrity protection, duplicate removal.
5. **SDAP Layer:** Quality of service.
![image](https://github.com/Rjesh2006/5G---For-Everyone-/assets/143868643/008c999d-aad5-4ba6-b763-5c21aaa73cfa)

