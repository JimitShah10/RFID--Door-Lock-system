# RFID--Door-Lock-system
This is a RFID door lock system using NodeMCU which stores its data to Firebase(Online database) 
## Components Needed
1.MFRC RC522(RFID Reader) with RFID Cards/Tags

2.NodeMCU

3.Bread board

4.Jumper Wires

5.USB cable

Download and install the libraries by following the below links:
https://github.com/FirebaseExtended/firebase-arduino/blob/master/src/Firebase.h

## Setting up Firebase
Once you are all set with components please follow simple steps mentioned below:

Connect NodeMCU with Computer.  
Open Arduino IDE.  
Goto ‘Tools’ and Select ‘Boards’.  
In board’s section, select ‘NodeMCU V1.0 (ESP-12E Module)’.  
Also select appropriate COM Port.  
After finding the “FIREBASE_HOST” and “FIREBASE_AUTH” following the steps mentioned below, edit this in sketch given below and upload.
