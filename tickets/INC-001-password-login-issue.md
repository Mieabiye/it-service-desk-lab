INC-001: Windows Login Failure



###### **1. Incident Details**

* **Incident ID**: INC-001
* **Category**: Account and Access
* **Priority**: Medium
* **Status**: Resolved (simulation)
* **Affected user**: User A
* **System**: Windows workstation
* **Incident type**: Password authentication failure



###### **2. Problem Description**

A user reports that they cannot sign into their Windows computer. The system displays a message indicating the password is incorrect.



The user needs access to the workstation to continue their work.



###### **3. Initial Assessment**

**Potential causes:**



* Caps Lock is enabled
* The wrong keyboard layout is selected
* The username or password was entered incorrectly
* The account is locked or disabled
* The password has expired



These are possible causes, not confirmed findings



###### **4. Troubleshooting Steps**

* Asked the user to verify the username
* Checked whether Caps Lock was enabled
* Asked the user to confirm the keyboard layout
* Asked the user to enter the password carefully without sharing it with support
* If the issue continued, checked the account status using an authorized administrative method
* If a password reset was required, followed the organization's approved identity-verification and password-reset procedure.



###### **5. Root Cause**

**Simulated finding**: The user had Caps Lock enabled while entering the password



###### **6. Resolution**

The user disabled Caps Lock and entered the correct password. Sign-in succeeded.



###### **7. Verification**

Confirmed that the user could sign in and access the Windows desktop



###### **8. Prevention and Recommendations**

* Check Caps Lock and keyboard layout when login failures occur.
* Never ask users to disclose their passwords.
* Follow identify-verification procedures before resetting accounts.
* Escalate persistent failures to the appropriate system administrator.



###### **9. Lessons Learned**

A structured troubleshooting process can resolve simple authentication problems quickly. Support staff should verify basic causes before escalating an incident.



###### **10. Practice Disclaimer**

This is a simulated training incident. No real user account or production system was accessed. 

