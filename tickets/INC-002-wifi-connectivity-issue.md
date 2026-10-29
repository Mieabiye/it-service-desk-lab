##### **INC-002: Wi-Fi Connectivity Issue**



###### **1. Incident Details**

**Incident ID**: INC-002

**Category**: Network Connectivity

**Priority**: Medium

**Status**: Resolved (simulation)

**Affected user**: User B

**System**: Windows workstation



###### **2. Problem Description**

The user reports that their Windows computer is connected to the office Wi-Fi network but cannot access websites. 



###### **3. Initial Assessment**

**Possible causes include**:



* Weak Wi-Fi signal.
* Incorrect network configuration.
* Router or access point problems.
* DNS resolution failure
* Temporary network outage



###### **4. Troubleshooting Steps**

* Confirmed that Wi-Fi was enabled
* Checked whether the computer was connected to the expected network.
* Checked whether other devices could access the internet.
* Opened Command Prompt and ran *ipconfig* to inspect the network configuration.
* Ran *ping 8.8.8.8* to test basic IP connectivity.
* Ran *nslookup example.com* to test DNS resolution.
* Reviewed the results to identify the likely cause.



###### **5. Root Cause**

**Simulated finding**: The computer could reach an external IP address but DNS name resolution was failing.



###### **6. Resolution**

The issue was escalated to the network administrator, who corrected the DNS configuration.



###### **7. Verification**

The user reopened the browser and successfully accessed websites after the DNS configuration was corrected.



###### **8. Prevention and Recommendations**

* Document network configuration changes
* Check whether an issue affects one device or multiple devices.
* Use approved troubleshooting commands.
* Escalate network configuration changes when administrator privileges are required.



###### **9. Lessons Learned**

Testing IP connectivity separately from DNS resolution helps narrow down the source of a network problem.



###### **10. Practice Disclaimer**

This is a simulated training incident. The described DNS failure and resolution are fictional, no production network was changed.

