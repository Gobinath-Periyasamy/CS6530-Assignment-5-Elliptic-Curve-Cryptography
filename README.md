# CS6530-Assignment-5-Elliptic-Curve-Cryptography
Assignment 5 Elliptic Curve Cryptography

Assignments for IIT CS6530 Cryptography Basics

**Name : Gobinath Periyasamy**

**Roll Number : CS21M501**

**Registered Mail id : janu.gobi@gmail.com**

Steps to Execute the Program:

  1.  To open the **ecc.exe** file.
  2.  To input a value. Eg : 56
  3.  To input b value. Eg : 76
  4.  To input message x point Eg : 45
  5.  To input message y point Eg : 34

Private and Public keys will be generated.

Given points are converted Cipher Texts Cipher x and Cipher y would be created from the message given using P, Q, R, G.

Then Original message is decrypted.

**Sample Ouput 1 :**

E:\IIT CS Prep\IIT Sem\Cryptography Basics\EllipticCurveCrypto>ecc.exe

Please enter a value : 56

Please enter b value : 76

The elliptic curve: y^2 mod 263 = (x^3+56x+76) mod 263


===================================================

P       : (2, 14)

Q       : (2, 249)

R       : (18, 135)

G       : (1, 50)

order of G : 50

Sender's public key = (1, 50)

Receiver's public key = (209, 67)

===================================================

Please enter the message points:

message_x co-ordinate : 45

message_y co-ordinate : 34

*************************************************
* **Your input message points : (45, 34)**
*************************************************

Encrypted message points using diffie hellman :

         (cipher_x,cipher_y) = ( 200, 174 )


*********************************************
* **Decrypted message points = (45, 34)**
*********************************************

--------**Decrypted points are equal to the given message  points**--------

Press any key to continue . . .


**Sample Ouput 2:

E:\IIT CS Prep\IIT Sem\Cryptography Basics\EllipticCurveCrypto>ecc.exe

Please enter a value : 45

Please enter b value : 65

The elliptic curve: y^2 mod 263 = (x^3+45x+65) mod 263


===================================================

P       : (4, 109)

Q       : (4, 154)

R       : (29, 118)

G       : (1, 30)

order of G : 20

Sender's public key = (1, 30)

Receiver's public key = (127, 50)

===================================================

Please enter the message points:

message_x co-ordinate : 78

message_y co-ordinate : 32

*************************************************

* **Your input message points : (78, 32)**

*************************************************

Encrypted message points using diffie hellman :

    (cipher_x,cipher_y) = ( 175, 22 )


*********************************************
* **Decrypted message points = (78, 32)**
*********************************************

--------**Decrypted points are equal to the given message points**--------

Press any key to continue . . .
