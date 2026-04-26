# ARP-spoofing Attack Analysis

## Objective

Demonstrate ARP Spoofing attack in a controlled lab environment and analyze its security impact.

## Tools Used

* Kali Linux
* Wireshark
* Linux Terminal
* VirtualBox 

## Network Topology

Attacker → Kali Linux
Victim → Target Machine
Gateway → Router

The attacker performs Man-in-the-Middle (MITM) by poisoning ARP tables.

## Attack Process

1. Identify victim IP address
2. Identify gateway IP address
3. Enable IP forwarding
4. Launch ARP spoofing attack using Ettercap
5. Intercept network traffic
6. Analyze packets using Wireshark

## Indicators of Compromise

* Duplicate ARP replies
* Unexpected MAC address changes
* Unusual network latency
* Suspicious traffic redirection

## Risk Level

High

## Impact

* Traffic interception
* Credential theft
* Session hijacking
* Data manipulation
* Man-in-the-Middle attack

## Mitigation

* Static ARP entries
* Dynamic ARP Inspection (DAI)
* VLAN segmentation
* HTTPS enforcement
* Network monitoring

## Conclusion

ARP Spoofing remains a dangerous local network attack when proper protections are not implemented.
Early detection and network segmentation significantly reduce the risk.
