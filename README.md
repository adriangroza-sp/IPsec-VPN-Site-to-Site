# Enterprise IPsec-VPN-Site-to-Site
This project demonstrates a Site-to-Site IPsec VPN tunnel using 2 Fortinet Firewalls

## Overview

This project demonstrates the implementation of a Site-to-Site IPsec VPN between two Fortinet firewalls. The VPN securely connects two separate LAN networks over an untrusted network, allowing hosts from different sites to communicate as if they were on the same private network.

The lab includes the configuration of IPsec Phase 1 and Phase 2 parameters, static routing, and firewall policies required to establish secure communication between the networks 192.168.1.0/24 and 192.168.2.0/24.

 ## Objectives
  
Configure a Site-to-Site IPsec VPN between two Fortinet firewalls.
Establish secure connectivity between two remote LAN networks.
Configure IKE Phase 1 settings to create a secure VPN tunnel.
Configure IPsec Phase 2 settings to protect data transmitted between sites.
Create static routes to direct traffic through the VPN tunnel.
Implement firewall policies to allow communication between the connected networks.
Test connectivity between hosts located on different sites.
Troubleshoot VPN, routing, and policy-related issues during deployment.

## Limitations
Low Scalability - Works well when we have a couple of sites but when we need to scale to many more sites management will become more complex as we ll need to configure and maintain them all
Fairly Complex Configuration / ( we need to aggree on Encryption, Hashing algorithms, Diffie Hellman Groups,Lifetime values,authentication methods 
Limited Visibility as traffic is encrypted


## Lab Environment
-EVE-NG
-Lab Components -2 Fortinet Firewall Devices /2 sites


## Software Release Version
FortiGate-VM64-KVM v6.4.0,build1579

## Topology
<img width="1281" height="532" alt="Site to Site IPSEC VPN tunnel" src="https://github.com/user-attachments/assets/344e010b-a6b5-4d6e-8235-312d4bf6e558" />


## Configuration 








