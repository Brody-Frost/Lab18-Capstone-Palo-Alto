
### <ins>Configure Networking</ins>

#### Configure interfaces:  
*Network > Interfaces > Ethernet*

#### Configure virtual router:  
*Network > Virtual Routers*    
- Create a default route 0.0.0.0/0

#### Configure interface management profile:  
*Network > Interface Mgmt*

### <ins>Configure Security Zones</ins>
*Network > Zones*  
- Internet: ethernet1/1
- Users: ethernet1/2
  - Configure User-ID
- Extranet: ethernet1/3

#### Create security zone tags  
*Objects > Tags*

### <ins>Verify Network Connectivity</ins>

- Internal host can ping 192.168.100.1
- SSH to firewall 192.168.1.1
- insrt img firewall pings ssh cli

### <ins>Configure NAT Policy Rules</ins>
*Policies > NAT*

### <ins>Configure Security Policy Rules</ins>
*Policies > Security*

### <ins>Create and Apply Security Profiles</ins>
*Policies > Security*
