# NETWORKWALKSMEWARD-BWALYA-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
LAB SETUP

Week 1 – Cybersecurity Lab Setup (VirtualBox & Kali Linux)
Objective
Successfully configured a cybersecurity lab environment using VirtualBox and Kali Linux.
Tasks Completed
- Installed VirtualBox.
- Imported the Kali Linux virtual machine.
- Configured a NAT Network (10.0.0.0/24).
- Assigned the static IP address 10.0.0.2/24 to Kali Linux.
- Enabled Shared Clipboard and Drag & Drop.
- Configured Shared Folders.
- Verified Internet connectivity.
Challenge Encountered
Although the IP address and NAT Network configuration were correct, Kali Linux could not access the Internet.
Troubleshooting Process
I investigated the network connections and discovered there were two active network profiles:
- Ethernet Connection
- Wired Connection
The duplicate Ethernet connection caused a networking conflict. After removing the unnecessary Ethernet connection and leaving the correct Wired Connection active, Internet connectivity was restored successfully.
Lessons Learned
- Correct IP configuration alone does not guarantee connectivity.
- Duplicate or conflicting network profiles can prevent Internet access.
- Systematic troubleshooting is essential when configuring virtual networking.
- Understanding VirtualBox NAT networking is important for building cybersecurity labs.
