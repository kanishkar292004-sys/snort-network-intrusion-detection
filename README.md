# Network Intrusion Detection using Signature-Based Approach (Snort)

## 📌 Project Overview
This project demonstrates a signature-based Intrusion Detection System using Snort. 
Snort monitors network traffic and matches it with predefined attack signatures to detect threats.

## 🎯 Objectives
- Analyze network traffic for malicious activity  
- Use Snort for real-time intrusion detection  
- Generate alerts for known attacks  
- Improve network security monitoring  

## 🏗️ Architecture
Traffic Capture → Snort Engine → Rule Matching → Alert Generation → Logs

## 🔐 Sample Snort Rule Used
alert icmp any any -> any any (msg:"ICMP Ping Detected"; sid:1000001;)

## 🛠️ Tools Used
- Snort IDS  
- Ubuntu Linux  
- Wireshark  

## ✅ Results
- Successfully detected known attacks  
- Generated real-time alerts  
- Improved threat response time
