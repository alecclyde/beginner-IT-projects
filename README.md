# Beginner-IT-projects
This repo is a list of interesting projects for people looking to get into IT.

## Pre-reqs
- Most of these projects require you to run a virtual machine, which works best on a semi-powerful computer.
  - Download the latest version of VirtualBox, this will allow you to install virtual machines on your computer: https://www.virtualbox.org/wiki/Downloads.
- If you have an old computer, that can substitute instead of building a virtual machine for some projects.

## Projects
- AdGuard Home - AdGuard Home is a network-wide software for blocking ads & tracking. After you set it up, it’ll cover ALL your home devices, and you don’t need any client-side software for that. 
- HomeAssistant - description
- Plex Media Server - description


## AdGuard Home
- Here is the GitHub you will be working out of for this project: [https://github.com/AdguardTeam/AdGuardHome#getting-started](https://github.com/AdguardTeam/AdGuardHome)
- With this project, you can control  network traffic comes in and out of your network. For example, if you have a Roku, Amazon TV, or some other smart media player, you can use a DNS blacklist that strictly removes advertizement and tracking data from that. **Be aware of what you are blocking, because it is possible to over-block and restrict access to good websites.**
  - Some popular DNS blacklists to consider. Make sure to research what each list covers, as they may overlap significantly. (Make sure to find and use the raw output) 
    - https://github.com/hagezi/dns-blocklists
    - https://github.com/curbengh/phishing-filter
    - https://github.com/AdguardTeam/AdGuardSDNSFilter

  - You should always include a Whitelist to make sure you cover the basics. (One of the main issues I had was advertisement links in Google not working, this fixes that)
    - https://raw.githubusercontent.com/hagezi/dns-blocklists/main/whitelist.txt
    - https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt
    - https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/optional-list.txt
    - https://raw.githubusercontent.com/hagezi/dns-blocklists/main/whitelist-referral.txt
    - https://raw.githubusercontent.com/SystemJargon/allowlists/main/lists/ios-basic-allowlist.txt
    - https://raw.githubusercontent.com/hl2guide/AdGuard-Home-Whitelist/main/whitelist.txt

## Home Assistant
- Follow the guide for the appropriate Operating System you would like to install (Note: if you are installing in VirtualBox, Windows or Linux is recommended. Go for Linux if you want to practice your command-line skills): [https://www.home-assistant.io/installation/](https://www.home-assistant.io/installation/)
- With HomeAssistant, you can install an AdGuard Home as an add-on. There are a ton of other integrations and add-ons to look at and consider. 

## Plex Media Server
- Follow this guide to install a Plex server: [https://support.plex.tv/articles/200264746-quick-start-step-by-step-guides/](https://support.plex.tv/articles/200264746-quick-start-step-by-step-guides/)


## Potential Projects **Work in progress**:
Network Monitoring: Set up a network monitoring system using tools like Nagios, Zabbix, or PRTG. Monitor network devices, services, and performance to identify and resolve issues proactively.

Firewall Configuration: Build and configure a firewall using open-source software like pfSense or OPNsense. Learn about network security, create firewall rules, and control traffic flow.

VLAN Setup: Create virtual LANs (VLANs) on your network switch to segment and isolate network traffic. Learn about VLAN tagging, trunking, and inter-VLAN routing.

Network File Sharing: Set up a network-attached storage (NAS) device using software like FreeNAS or OpenMediaVault. Enable file sharing protocols such as SMB, NFS, or FTP to share files across the network.

VPN Server Configuration: Install and configure a VPN server using software like OpenVPN or WireGuard. Learn about VPN protocols, encryption, and secure remote access.

Bandwidth Monitoring and Traffic Shaping: Use tools like NetFlow Analyzer, ntop, or tc (Traffic Control) to monitor network bandwidth usage and implement traffic shaping techniques to prioritize certain types of traffic.

Network Security Assessment: Conduct a network security assessment using tools like Nmap, Wireshark, or OpenVAS. Scan and analyze network vulnerabilities, assess security configurations, and recommend improvements.

Network Load Balancing: Set up a load balancer using software like HAProxy or nginx. Distribute incoming network traffic across multiple servers to improve performance, reliability, and scalability.

Network Virtualization: Explore network virtualization technologies like VMware NSX, Cisco ACI, or Open vSwitch. Create virtual networks, implement network overlays, and learn about software-defined networking (SDN).

Network Access Control: Deploy a network access control (NAC) solution like PacketFence or FreeRADIUS. Learn about network authentication, authorization, and enforcement mechanisms.
