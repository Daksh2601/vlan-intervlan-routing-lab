# vlan-intervlan-routing-lab
Home lab simulating how real corporate networks segment departments using VLANs. Three isolated networks (IT, HR, Guest) route through a Layer 3 switch, with firewall-style ACLs blocking Guest access to internal resources. Documented with full topology diagram and configs.

<img width="1228" height="1076" alt="image" src="https://github.com/user-attachments/assets/2d40aff1-b54e-49c2-8c56-113ce2ff38aa" />

## VLANs Configured
- VLAN 10: IT (192.168.10.0/24)
- VLAN 20: HR (192.168.20.0/24)
- VLAN 30: Guest (192.168.30.0/24)

## Key Concepts Demonstrated
- VLAN segmentation
- 802.1Q trunking
- SVI-based inter-VLAN routing
- ACL enforcement for Guest isolation

## Tools Used
- Cisco Packet Tracer
- Draw.io
