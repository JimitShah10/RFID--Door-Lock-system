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

## Setting Up Firebase Console
If you are using Firebase first time then you may take some time to setting it up. Have patience and follow these steps.

1. If you have Gmail id then you don’t need to Sign Up for firebase, if you don’t have Gmail id then Sign Up for one and then you can go to next step.

2. Open your browser and go to “firebase.google.com”

3. At the right top corner go to “Go to Console”

## How to use this.
Once you are all set with components please follow simple steps mentioned below:

Connect NodeMCU with Computer.  
Open Arduino IDE.  
Goto ‘Tools’ and Select ‘Boards’.  
In board’s section, select ‘NodeMCU V1.0 (ESP-12E Module)’.  
Also select appropriate COM Port.  
After finding the “FIREBASE_HOST” and “FIREBASE_AUTH” following the steps mentioned below, edit this in sketch given below and upload.
