# 1.0 Pre-requisite Information
## Virtualisation Software
VMware Workstation

## 1.1 Operating Systems
Windows Server 2019

## 1.2 Hostname Naming Convention
The hostnames used in this homelab environment will be in the following pattern:
{Physical_or_Virtual}{OS}{XXX}
{Physical_or_Virtual} = whether the Configuration Item is a physical or virtual computer.
{OS} = Windows or Linux.
{XXX} = determines the number of XXX Configuration Items available. This field is paired with {OS}.
<br />
For example: VMW1001

## 1.3 Defensive Software (Blue Team)

## 1.4 Offensive Software (Red Team)
nmap
BloodHound - https://github.com/BloodHoundAD/BloodHound
mimikatz

# 2.0 Setting up the Homelab Environment
## 2.1 Active Directory

## 2.2 Domain Name System (DNS)
Follow the below steps to setup DNS on a Windows Server:
<!-- 
- Disable IPv6 (ncpa.cpl) on all CIs. 
- setup Foward and Reverse Lookup Zone
- DNS > FLZ > {zone} > Name Servers. Ensure the DNS server is in the list using its IPv4 address. Delete the IPv6 address if any.
-->

## 2.3 Dynamic Host Control Protocol (DHCP)
<!--
After installing the DHCP package and creating a scope, you must Authorize the service. You should notice that the icons for IPv4 and IPv6 change from RED to GREEN.
-->
