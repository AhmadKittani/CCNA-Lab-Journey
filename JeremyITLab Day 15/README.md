# Jeremy's IT Lab - Day 15

## Lab Overview
- Subnetted all 4 LANs with the point-to-point connection
- Assigned the first usable addresses of all LANs to their PCs and Default Gateways

## Problems Encountered & Solutions

**Issue:** IP addressing configuration conflict on router interfaces

**Solution:** I assigned LAN 1's Default Gateway IP address to LAN2's port in R1, and vice versa.

## Key Learning
During this problem I learned that the `no` command is required when swapping 2 ports' IP addresses.
