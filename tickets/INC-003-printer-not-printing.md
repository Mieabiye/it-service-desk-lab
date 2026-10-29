##### **INC-003: Windows Printer Not Printing**



###### **1. Incident Details**

**Incident ID**: INC-003

**Category**: Hardware and Peripheral Support

**Priority**: Medium

**Status**: Resolved (simulation)

**Affected user**: User C

**System**: Windows workstation

**Device**: Network printer



###### **2. Problem Description**

The user reports that documents sent to the office printer remain in the print queue and no ages are printed.



###### **3. Initial Assessment**

**Possible causes include:**



* Printer is powered off or disconnected
* Incorrect printer is selected
* Paper jam or empty paper try
* Print queue is stuck
* Printer driver or network connection problem



###### **4. Troubleshooting Steps**

* Confirmed the selected printer was correct
* Checked the printer's power, display, paper supply and error indicators
* Confirmed whether other users could print
* Opened Windows printer settings and inspected the print queue
* Checked whether the printer showed an offline status
* Cleared the affected user's stuck test job using the approved procedure
* Sent a small test document to the printer



###### **5. Root Cause**

Simulated finding: A print job was stuck in the user's print queue and prevented subsequent documents from printing.



###### **6. Resolution**

Removed the stuck job from the queue and submitted a new test document.



###### **7. Verification**

The test document printed successfully and the user confirmed that printing had resumed.



###### **8. Prevention and Recommendations**

* Check the printer's status before troubleshooting drivers
* Confirm whether the issue affects one user or several users
* Remove only the affected jobs unless broader action is authorized
* Escalate persistent queue or driver problems to the appropriate IT administrator.



###### **9. Lessons Learned**

Checking the print queue and basic printer status can resolve common printing problems without unnecessary driver changes.



###### **10. Practice Disclaimer**

This is a simulated training incident. The root cause and resolution are fictional, no real printer or production system was accessed.

