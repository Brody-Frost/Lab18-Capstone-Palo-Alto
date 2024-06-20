
### <ins>Configure Networking</ins>

#### Configure interfaces:  
*Network > Interfaces > Ethernet*

#### Configure virtual router:  
*Network > Virtual Routers*    
- Create a default route 0.0.0.0/0
  
  <img src="./Images/virtual-router3.PNG" alt="image" width="600"/>

#### Configure interface management profile:  
*Network > Interface Mgmt*

### <ins>Configure Security Zones</ins>
*Network > Zones*  
- Internet: ethernet1/1
- Users: ethernet1/2
  - Configure User-ID
- Extranet: ethernet1/3

#### Create security zone tags:  
*Objects > Tags*

### <ins>Verify Network Connectivity</ins>

- Internal host can ping 192.168.100.1
- SSH to firewall 192.168.1.1
- insrt img firewall pings ssh cli

### <ins>Configure NAT Policy Rules</ins>
*Policies > NAT*  

Source NAT:
- Users_to_Internet
- Extranet_to_Internet

### <ins>Configure Security Policy Rules</ins>
*Policies > Security*
- Block_Bad_URLs
- Users_to_Extranet
- Users_to_Internet
- Extranet_to_Internet

#### Create security policy tags:  
*Objects > Tags*

#### Testing security policies:

### <ins>Create and Apply Security Profiles</ins>
*Policies > Security*
- Antivirus: Corp-AV
- Anti-Spyware: Corp-AS
- Vulnerability Protection: Corp-Vuln
- URL Filtering: Corp-URL
- File Blocking: Corp-FB
- WildFire Analysis: Corp-WF
