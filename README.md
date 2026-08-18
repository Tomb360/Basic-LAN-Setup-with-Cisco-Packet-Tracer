# <p align="center">Cisco Packet Tracer — Basic LAN Setup</p>

<p align="center">A simulated small office network built in Cisco Packet Tracer demonstrating physical device setup, wired and wireless connectivity, DHCP configuration, static IP assignment, and end-to-end connection testing.</p>

---

## <p align="center">Component Setup</p>

### <p align="center">Devices Used</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/500288ac-42e6-4c8e-85ba-0eb666ac347b" alt="Component setup" width="800"/>
</p>

<p align="center">Network built using 3 PCs, 1 Laptop, 1 Printer, 1 Router, 1 Switch, and 1 Wireless Router.</p>

---

## <p align="center">Physically Connecting Devices</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/77b5f383-0d54-4bde-ab2c-9c1ac5a4f6f7" alt="PCs connected to switch" width="800"/>
</p>

<p align="center">
  
  Connected each PC to the Switch using the copper straight-through cable.

  Connected the Printer to the Switch

Connected the Router to the Switch using a straight-through cable 

Used a crossover cable to connect WirelessRouter’s Internet port to Router’s GigabitEthernet 0/1.
</p>


---

## <p align="center">Configuring the Router</p>

### <p align="center">GigabitEthernet 0/0 Interface</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bdef42a0-34ce-4a3d-a927-90bf4fc07f94" alt="GigabitEthernet 0/0 config" width="800"/>
</p>

<p align="center">GigabitEthernet 0/0 configured as the gateway interface for the wired LAN.</p>

### <p align="center">GigabitEthernet 0/1 Configuration</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/304e42b6-3185-4ac5-8664-25b9e95012de" alt="GigabitEthernet 0/1 config" width="800"/>
</p>

<p align="center">GigabitEthernet 0/1 configured to connect to the Wireless Router's Internet port.</p>

### <p align="center">DHCP Pool Setup for Wired Devices</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c4622131-45a6-4959-9cde-8bc612352bf4" alt="DHCP pool wired" width="800"/>
</p>

<p align="center">DHCP pool configured on the Router to automatically assign IP addresses to wired devices on the LAN.</p>

### <p align="center">DHCP Pool for Wireless Devices</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/dc4fad4f-1465-496f-a268-edb1c6dd8f4f" alt="DHCP pool wireless" width="800"/>
</p>

<p align="center">Separate DHCP pool configured to serve IP addresses to wireless devices connecting via the Wireless Router.</p>

---

## <p align="center">Configuring the Wireless Router</p>

### <p align="center">SSID Name</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7b1bfc58-a33c-4cce-927a-fc381f1949af" alt="SSID configuration" width="800"/>
</p>

<p align="center">Wireless network SSID configured to identify the network.</p>

### <p align="center">Passphrase Security Setup</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/44e11911-8155-4572-800e-5b88cd670a35" alt="Passphrase security" width="800"/>
</p>

<p align="center">WPA2 passphrase configured to secure the wireless network.</p>

### <p align="center">Configuring LAN Settings</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/445f370c-f74e-40e7-8293-fa3d0ed3ade0" alt="Wireless router LAN settings" width="800"/>
</p>

<p align="center">LAN settings on the Wireless Router configured to sit within the correct subnet.</p>

---

## <p align="center">Laptop Configuration</p>

### <p align="center">Adding Wireless Module in Physical Tab</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/3c52b60b-ce69-4964-9f21-534b690805c8" alt="Adding wireless module" width="800"/>
</p>

<p align="center">Wireless network adapter module added to the Laptop via the Physical Tab to enable Wi-Fi connectivity.</p>

### <p align="center">Connecting to Wireless Network</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cf3b585b-7c16-479d-8dca-abbc33fd9d6e" alt="Connecting to wireless network" width="800"/>
</p>

<p align="center">Laptop configured to connect to the SSID using the configured passphrase.</p>

### <p align="center">Successful Connection</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ae92aca5-1798-4e46-87c6-eeb1fce23bec" alt="Successful wireless connection" width="800"/>
</p>

<p align="center">Laptop confirmed connected to the wireless network and assigned an IP address via DHCP.</p>

---

## <p align="center">Printer Configuration</p>

### <p align="center">Static IP Assignment</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2f0513b3-30df-4c5c-a9ed-dc1457b5f516" alt="Printer static IP" width="800"/>
</p>

<p align="center">Printer assigned a static IP address outside the DHCP range to mimic real-world best practice, ensuring the address never changes.</p>

---

## <p align="center">Wired PC Setup</p>

### <p align="center">Setting IP Configuration to DHCP</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c6a51c5c-1678-46e5-91e2-b0216c258751" alt="PC DHCP configuration" width="800"/>
</p>

<p align="center">All 3 PCs set to obtain an IP address automatically via DHCP from the Router.</p>

---

## <p align="center">Connection Tests</p>

### <p align="center">Verifying IP of Wired PC and Pinging Router</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/91e75dce-2bb0-41d9-9b54-8e30d64bb180" alt="IP verification and ping test" width="800"/>
</p>

<p align="center">IP address verified on a wired PC using ipconfig in the command prompt, followed by a successful ping to the Router's gateway address.</p>

### <p align="center">Connection to Printer IP Check</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/33cb9b89-b466-4da3-aac5-cf66a293e4d2" alt="Printer IP ping test" width="800"/>
</p>

<p align="center">Ping test carried out from a PC to the Printer's static IP address to confirm network reachability.</p>

---

## <p align="center">Final Successful Configuration</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c0ab63fa-4019-468e-9540-823ee640f474" alt="Final network configuration" width="800"/>
</p>

<p align="center">Completed network topology showing all devices connected, configured, and communicating successfully across both wired and wireless segments.</p>

---

## <p align="center">Skills Demonstrated</p>

<p align="center">Cisco Packet Tracer &nbsp;·&nbsp; LAN Design &nbsp;·&nbsp; Router Configuration &nbsp;·&nbsp; DHCP Setup &nbsp;·&nbsp; Wireless Networking &nbsp;·&nbsp; Static IP Assignment &nbsp;·&nbsp; Network Cabling &nbsp;·&nbsp; Connection Testing &nbsp;·&nbsp; Subnetting Fundamentals</p>
