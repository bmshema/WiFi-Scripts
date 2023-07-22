# WiFi-Scripts
Some baseline scripts for Wi-Fi Analysis, network mapping, and enrichment.

### tshark_baseline.sh: 
Executes 12 tshark commands to aid in wireless network mapping, resulting in csv format files suitable for import into Maltego or other network mapping applications.
  - Access Point Information
  - Connected Clients
  - Probe Requests
  - DHCP Server
  - DHCP Clients
  - ARP
  - DNS Client
  - HTTP Client
  - Browser
  - MDNS
  - ICMP
  - TCP

![example](https://github.com/bmshema/Baseline-WiFi-Scripts/assets/92175742/e1662979-639f-4edd-bb19-9c7ffebbb01d)

### twoPlaces.sh: 
Takes input from packet captures collected from two separate locations and identifies MAC addresses present at both locations. Resulting output is in bothplaces.txt numbered by how many locations a MAC address was present in.

