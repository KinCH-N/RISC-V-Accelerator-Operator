# RISC-V-Accelerator-Operator

**RISC-V Accelerator Operator** is an open-source project aimed at providing support for RISC-V architecture hardware accelerator cards in Kubernetes and KubeVirt environments. It includes two main components:

- **RISC-V Device Plugin**: Allows Kubernetes or KubeVirt clusters to recognize and manage hardware accelerator cards that support the RISC-V architecture, providing hardware resource discovery and allocation.
  
- **RISC-V VFIO-Manager**: Enables virtual machines to access RISC-V accelerator hardware directly (via VFIO), allowing for PCI device passthrough operations to efficiently utilize physical accelerator cards.

This operator can seamlessly integrate into K8s / KubeVirt clusters, offering users an efficient and flexible hardware acceleration solution, supporting the development and operation of performance-intensive applications.

### Features

- **Hardware Acceleration Support**: Supports RISC-V architecture hardware accelerator cards, providing acceleration resources in the cluster.
  
- **Device Plugin Support**: Fully integrated with Kubernetes and KubeVirt, supporting hardware resource discovery and management.
  
- **VFIO Management**: Allows virtual machines to directly pass through hardware resources via VFIO, fully utilizing hardware acceleration performance.
  
- **Efficient and Easy to Use**: Configures hardware acceleration resources automatically, simplifying user operations.
  
- **Open Source Community Support**: This project is open-source and encourages community contributions and improvements.
