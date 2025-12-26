# Password-Based-Door-Lock-System.



A hardware-based password lock system designed using an 8-bit comparator (IC 7485) to verify user input against a stored password. The system enhances security by tracking incorrect attempts and enforcing timed lockouts.



###### **Key Features**

* Password verification using IC 7485
* Failed-attempt tracking via IC 4017 counter
* Time-based lockouts using 555 timer
* Auto-reset on successful authentication or timeout
* Escalating security: 30-minute and 1-hour lock blocks





###### **Block Diagram**



![Password Lock Output](Block\_Diagram.png)



###### **Working Overview**



* Correct password → system unlocks and resets timers/counters
* Wrong password → attempts counted within a time window
* Multiple consecutive failures → system temporarily locked
* Continued failures → extended lockout for enhanced security



###### **Application**



Suitable for secure access control in doors, lockers, and embedded hardware systems.




###### Project Status



✅ Completed — Baseline implementation

🔧 Open for enhancements and upgrades

###### **Contributors**

Nazimuddin Ahmed (1706168), Joy Saha (1706189), Ishtiaque Ahmed (1706190), Tasnim Rahman (1706191), Aong Shay Sing Marma (1706195)
Department of Electrical & Electronic Engineering, Bangladesh University of Engineering and Technology (BUET)

#### **License**



This project is for academic and educational purposes.

