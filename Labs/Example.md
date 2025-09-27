# Wireshark Traffic Analysis Lab

**Date:** Sept 2025  
**Objective:** Analyze HTTP traffic for suspicious activity  
**Tools:** Wireshark, Ubuntu VM  

## Method
1. Captured packets from lab VM using Wireshark  
2. Filtered by HTTP protocol  
3. Identified plaintext credentials being transmitted  

## Findings
- Found unencrypted credentials → highlighted security risk  
- Recommended TLS/HTTPS and stronger passwords  

## Lessons Learned
- Importance of encrypted traffic  
- Using filters to analyze large captures efficiently
