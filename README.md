# Core-5g-slide
# 5G Core Network Overview

This document provides an overview of 5G mobile network architecture and key concepts as described in the CORE 5G document.

## Contents

- [Evolution from 4G to 5G](#evolution-from-4g-to-5g)
- [5G Architecture](#5g-architecture)
  - [Control/User Plane Separation (CUPS)](#controluser-plane-separation-cups)
  - [Virtualization](#virtualization) 
  - [Service-Based Architecture (SBA)](#service-based-architecture-sba)
  - [Network Functions](#network-functions)
- [Protocols and Interfaces](#protocols-and-interfaces)
  - [NAS, GTP, HTTP/2, REST APIs](#nas-gtp-http2-rest-apis)
- [5G Concepts](#5g-concepts)
  - [Network Slicing](#network-slicing)
  - [Quality of Service (QoS)](#quality-of-service-qos)
- [Use Cases](#use-cases)
  - [Enhanced Mobile Broadband (eMBB)](#enhanced-mobile-broadband-embb)
  - [Ultra-Reliable Low Latency Communications (URLLC)](#ultra-reliable-low-latency-communications-urllc)
  - [Massive Machine Type Communications (mMTC)](#massive-machine-type-communications-mmtc)

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
