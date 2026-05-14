# <p align="center">Cisco Packet Tracer — Basic LAN Setup</p>

<p align="center">A simulated small office network built in Cisco Packet Tracer demonstrating physical device setup, wired and wireless connectivity, DHCP configuration, static IP assignment, and end-to-end connection testing.</p>

---

## <p align="center">Component Setup</p>

### <p align="center">Devices Used</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504551092254412820/image.png?ex=6a0765e5&is=6a061465&hm=3fffe70c5653f3ee9687fc105e9720ee317995861c577a15554cd167b89eb1da&" alt="Component setup" width="800"/>
</p>

<p align="center">Network built using 3 PCs, 1 Laptop, 1 Printer, 1 Router, 1 Switch, and 1 Wireless Router.</p>

---

## <p align="center">Physically Connecting Devices</p>


<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504552576614535220/image.png?ex=6a076747&is=6a0615c7&hm=1f60f2f4313891ec748af6898a84e4da28f2ea5b85587ed2c740188539ab0274&" alt="PCs connected to switch" width="800"/>
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
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504554415280099398/image.png?ex=6a0768fd&is=6a06177d&hm=863b4bf30ddac9cefd33b481114ae5a43f36d3ce9a0337452e4e8e90dbd2397e&" alt="GigabitEthernet 0/0 config" width="800"/>
</p>

<p align="center">GigabitEthernet 0/0 configured as the gateway interface for the wired LAN.</p>

### <p align="center">GigabitEthernet 0/1 Configuration</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504555063496937702/image.png?ex=6a076998&is=6a061818&hm=7889c328230d3223685dcc3fe6a30df54adb03c18eb630ffc4931ae414745e57&" alt="GigabitEthernet 0/1 config" width="800"/>
</p>

<p align="center">GigabitEthernet 0/1 configured to connect to the Wireless Router's Internet port.</p>

### <p align="center">DHCP Pool Setup for Wired Devices</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504555556730441840/image.png?ex=6a076a0e&is=6a06188e&hm=c563dbc2d9d4799053e04c7498a48d82f90e515db0a50ea49536bbd38615ba2d&" alt="DHCP pool wired" width="800"/>
</p>

<p align="center">DHCP pool configured on the Router to automatically assign IP addresses to wired devices on the LAN.</p>

### <p align="center">DHCP Pool for Wireless Devices</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504557238197555301/image.png?ex=6a076b9e&is=6a061a1e&hm=b142e6a2189bcd30e974e14130a1f54f0ad921c0c33b164c0f90b7dd1ee126ae&" alt="DHCP pool wireless" width="800"/>
</p>

<p align="center">Separate DHCP pool configured to serve IP addresses to wireless devices connecting via the Wireless Router.</p>

---

## <p align="center">Configuring the Wireless Router</p>

### <p align="center">SSID Name</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504559527398477914/image.png?ex=6a076dc0&is=6a061c40&hm=a64c973209bc82960d4850435b77aa558950f12b908663d872f9f71efd9b2a79&" alt="SSID configuration" width="800"/>
</p>

<p align="center">Wireless network SSID configured to identify the network.</p>

### <p align="center">Passphrase Security Setup</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504559785247506492/image.png?ex=6a076dfe&is=6a061c7e&hm=b7fb27c27f2e53dc14ef70eb4428384fc88488c72335b1a707df4393d188d8ae&" alt="Passphrase security" width="800"/>
</p>

<p align="center">WPA2 passphrase configured to secure the wireless network.</p>

### <p align="center">Configuring LAN Settings</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504560161073660036/image.png?ex=6a076e57&is=6a061cd7&hm=4e5d741deabd9d3c0fda5af853dbe13863e99f1c1a030045ada0d99672db960e&" alt="Wireless router LAN settings" width="800"/>
</p>

<p align="center">LAN settings on the Wireless Router configured to sit within the correct subnet.</p>

---

## <p align="center">Laptop Configuration</p>

### <p align="center">Adding Wireless Module in Physical Tab</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504563913403142245/image.png?ex=6a0771d6&is=6a062056&hm=867d623533ac6008dc674bf09ea3fad5c969a315bcc664b32590da47c61cc2f9&" alt="Adding wireless module" width="800"/>
</p>

<p align="center">Wireless network adapter module added to the Laptop via the Physical Tab to enable Wi-Fi connectivity.</p>

### <p align="center">Connecting to Wireless Network</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504564246346862624/image.png?ex=6a077225&is=6a0620a5&hm=9ecc2eb47f35b0b40266fd311d6723814547500a003ccadc9b9cacdfd91b15e4&" alt="Connecting to wireless network" width="800"/>
</p>

<p align="center">Laptop configured to connect to the SSID using the configured passphrase.</p>

### <p align="center">Successful Connection</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504564358686969967/image.png?ex=6a077240&is=6a0620c0&hm=2e381fcc0884f8066b3b0fc4646f9af08413f4dd349dc4139933a4a6d8431da4&" alt="Successful wireless connection" width="800"/>
</p>

<p align="center">Laptop confirmed connected to the wireless network and assigned an IP address via DHCP.</p>

---

## <p align="center">Printer Configuration</p>

### <p align="center">Static IP Assignment</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504565239562113024/image.png?ex=6a077312&is=6a062192&hm=7f60b61f71ab418cd01eab661bb6336abb1d8304c32911a00f8d952a6db1326d&" alt="Printer static IP" width="800"/>
</p>

<p align="center">Printer assigned a static IP address outside the DHCP range to mimic real-world best practice, ensuring the address never changes.</p>

---

## <p align="center">Wired PC Setup</p>

### <p align="center">Setting IP Configuration to DHCP</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504566144780992655/image.png?ex=6a0773ea&is=6a06226a&hm=117e614f5dbd58c1604f4c8be3c15326e04773aa42835ee5295c598dfc228d0c&" alt="PC DHCP configuration" width="800"/>
</p>

<p align="center">All 3 PCs set to obtain an IP address automatically via DHCP from the Router.</p>

---

## <p align="center">Connection Tests</p>

### <p align="center">Verifying IP of Wired PC and Pinging Router</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504566767387676752/image.png?ex=6a07747e&is=6a0622fe&hm=d14d728d02b3a3c951e304dda72c25f0f2ab4cfd661985c1c4fc2577077935d2&" alt="IP verification and ping test" width="800"/>
</p>

<p align="center">IP address verified on a wired PC using ipconfig in the command prompt, followed by a successful ping to the Router's gateway address.</p>

### <p align="center">Connection to Printer IP Check</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504572164261806251/image.png?ex=6a077985&is=6a062805&hm=026c7a0384f75844073d8bd90d85870fd8d4efb5af3762011b8b1db014a44d07&" alt="Printer IP ping test" width="800"/>
</p>

<p align="center">Ping test carried out from a PC to the Printer's static IP address to confirm network reachability.</p>

---

## <p align="center">Final Successful Configuration</p>

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1504550793230155847/1504584727279964351/image.png?ex=6a078538&is=6a0633b8&hm=23fce3af0c09d4cafe767539ca7c862774d7c7b8d1b5406042bfc66bb0dc5645&" alt="Final network configuration" width="800"/>
</p>

<p align="center">Completed network topology showing all devices connected, configured, and communicating successfully across both wired and wireless segments.</p>

---

## <p align="center">Skills Demonstrated</p>

<p align="center">Cisco Packet Tracer &nbsp;·&nbsp; LAN Design &nbsp;·&nbsp; Router Configuration &nbsp;·&nbsp; DHCP Setup &nbsp;·&nbsp; Wireless Networking &nbsp;·&nbsp; Static IP Assignment &nbsp;·&nbsp; Network Cabling &nbsp;·&nbsp; Connection Testing &nbsp;·&nbsp; Subnetting Fundamentals</p>
