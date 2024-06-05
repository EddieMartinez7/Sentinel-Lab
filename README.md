Failed RDP to IP Geolocation Information


The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
![IPGeolocation Security Logs](https://github.com/7nani-x/Sentinel-Lab/assets/157913408/37d1a644-d6c9-458d-9381-ec861ecca517)
