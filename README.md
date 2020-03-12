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
4. Click on “Add project”  
5. Input your Project Name.  
6. Accept the terms and condition, Create project and click on “Continue”  
You have successfully created your project. Look for the Host Name and Authorization Key also known as Secret Key. For this, follow steps given below:  
7. Go to Settings Icon(Gear Icon) and click on “Project Settings”  
8. Now click on “Service Accounts”  
9. You can see two options “Firebase admin SDK” and “Database Secrets”  
10. Click on “Database Secrets”  
11. Scroll on your project name and ”Show” option appears at right side of your project  
12. Click on “Show” and now you can see secret key created for your project   
13. Copy the secret key and save it to notepad. This is your “FIREBASE_AUTH” string which we have written in Arduino program above.  
14. Now go to “Database” on left control bar and click on it  
15. Scroll down and click on “Create Database”  
16. Choose “Start in test mode” and click on “Enable”  
17. Now your database is created and you will have to come to this section again to read the ID card  
18. Now just above the database you  can see  
19. Just copy “your_project_name.firebaseio.com” without any slash and https and save it again to notepad just you had saved for secret key  
20. This is your “FIREBASE_HOST” string which we have written in Arduino program above  
21. You can explore the firebase but let’s finish the tutorial first.  
Now put “FIREBASE_HOST” and “FIREBASE_AUTH” in Arduino program and upload the sketch. And we are done with setting up both sections. Complete Arduino Program is given at the end.  

## How to use this.
Once you are all set with components please follow simple steps mentioned below:

Connect NodeMCU with Computer.  
Open Arduino IDE.  
Goto ‘Tools’ and Select ‘Boards’.  
In board’s section, select ‘NodeMCU V1.0 (ESP-12E Module)’.  
Also select appropriate COM Port.  
After finding the “FIREBASE_HOST” and “FIREBASE_AUTH” following the steps mentioned below, edit this in sketch given below and upload.
