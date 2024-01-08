
# 5G Core Network Overview

This document provides an overview of 5G mobile network architecture and key concepts as described in the CORE 5G document.

## Contents

- Evolution from 4G to 5G
- 5G Architecture
  - Control/User Plane Separation (CUPS)
  - Virtualization
  - Service-Based Architecture (SBA)
  - Network Functions
- Protocols and Interfaces
  - NAS, GTP, HTTP/2, REST APIs
- 5G Concepts
  - Network Slicing
  - Quality of Service (QoS)
- Use Cases
  - Enhanced Mobile Broadband (eMBB)
  - Ultra-Reliable Low Latency Communications (URLLC)
  - Massive Machine Type Communications (mMTC)

## Summary

The 5G architecture evolves from 4G networks with the separation of control and user planes, increased virtualization, and a service-based architecture based on REST APIs.

Key new components include User Plane Function (UPF), Access and Mobility Management Function (AMF), Session Management Function (SMF), Network Slice Selection Function (NSSF), and Network Repository Function (NRF). Legacy protocols like GTP are replaced by HTTP/2 in some places.

5G introduces flexibility via network slicing, allowing multiple logical networks to be created on top of shared physical infrastructure. More granular Quality of Service management is also supported compared to 4G.

The major 5G use cases are:

- Enhanced Mobile Broadband (eMBB) for high-speed data
- Ultra-Reliable Low Latency Communications (URLLC) for mission-critical apps
- Massive Machine Type Communications (mMTC) for massive IoT

The 5G core architecture allows scalability, automation and faster deployment of new services compared to previous cellular generations.

## References

- CORE 5G document
- 3GPP Standards
