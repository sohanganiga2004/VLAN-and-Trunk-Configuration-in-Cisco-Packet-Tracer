# VLAN-and-Trunk-Configuration-in-Cisco-Packet-Tracer

**Configuring VLAN and Trunk in Cisco Packet Tracer Using 2 Switches and 1 Router**

In this project, two VLANs were configured on two Cisco switches to achieve network segmentation. The following steps were performed:

1. **VLAN Creation**:
   - Created two VLANs (VLAN 10 and VLAN 20) on both switches.
   - Assigned specific ports on each switch to the respective VLANs to separate the network traffic.

2. **Trunk Configuration**:
   - Configured trunk ports between the two switches to carry traffic for multiple VLANs across a single physical link.
   - Used 802.1Q encapsulation to ensure VLAN tagging and proper traffic management across the trunk link.

3. **Inter-VLAN Routing**:
   - Configured a router to enable communication between the two VLANs.
   - Set up sub-interfaces on the router for each VLAN and assigned IP addresses to facilitate routing between VLAN 10 and VLAN 20.

This configuration ensures efficient network segmentation and communication between VLANs while maintaining a scalable and manageable network structure.
