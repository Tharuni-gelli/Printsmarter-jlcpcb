# Printsmarter-jlcpcb
Development of nation starts only when rural development starts. Rural development is one of the major areas of prominence these days. Emerging technologies can provide the best solutions to the problems that are prevailing in the rural areas. Considering this fact we have chosen the following problem statement. As we are well aware that whenever a person visits bank he/she has to fill the withdrawal or deposit slips for money transaction as per the bank norms. This actually causes problem to the senior citizens and illiterates as the slips should be filled in English. Sometimes minute errors that are committed while filling the form makes the slip unacceptable which will lead to the wastage of time for both the individual and the bank. To overcome these difficulties and to make the process of money transactions simpler, smarter we will install two printing devices- one for the withdrawal and the other for the deposit.

![image](https://user-images.githubusercontent.com/101914547/159105974-f50d49d0-f73a-4ccf-a34f-1ce21a232e8b.png)
https://jlcpcb.com/rel

Introduction:

As we are well aware that whenever a person visits bank he/she has to fill the withdrawal or deposit slips for money transaction as per the bank norms. This actually causes problem to the senior citizens and illiterates as the slips should be filled in English. Sometimes minute errors that are committed while filling the form makes the slip unacceptable which will lead to the wastage of time for both the individual and the bank. To overcome these difficulties and to make the process of money transactions simpler, smarter we will install two printing devices- one for the withdrawal and the other for the deposit. The process of our system follows the steps in the following manner. Initially the person who wants to deposit or withdraw comes to the respective device where biometric authentication will be performed. The device will be connected to the bank database through Wi-Fi. The account holder details will be fetched and the person will be provided assistance regarding the amount they want to withdraw or deposit. The additional feature included in this device is voice assistance. It will assist the user in English and the native language based on the location it is installed in. One’s who are comfortable with entering amount through keypad can use it or they can take the help of voice assistance. Unlike the withdrawal device, in the deposit machine there will be an additional device for the denomination. In this way our solution provides a unique and innovative way of money transactions which can be employed in rural banks.  

Components Required:

Arduino UNO- 

An open source microcontroller which is based on Atmega328p. The board has set of analog and digital output pins which can be interfaced to obtain our desired application. The board has 14 digital I/O pins. 6 analog I/O pins. Out of 14 digital I/O pins 6 pins are capable of producing PWM outputs. We can program it using Arduino Integrated Development Environment.

![image](https://user-images.githubusercontent.com/101914547/159106096-27647d18-2eed-40e4-b963-05db56b71195.png)

ESP8266-

The ESP8266 is a Wi-Fi microchip, with built-in networking software, and microcontroller capability. ESP8266 comes with capabilities of 2.4 GHz Wi-Fi (802.11 b/g/n, supporting WPA/WPA2), general-purpose input/output (16 GPIO), Inter-Integrated Circuit (I²C) serial communication protocol, analog-to-digital conversion (10-bit ADC),
Serial Peripheral Interface (SPI), I²S interfaces with DMA, UART, and (PWM).To communicate with the ESP8266 module, microcontroller needs to use set of AT commands. Microcontroller communicates with ESP8266-01 module using UART having specified Baud rate.

![image](https://user-images.githubusercontent.com/101914547/159106126-c0f4212a-3631-4e7b-9dd5-db9c85038bb6.png)


Finger print module (3000) GTM-5210F52-

A module which is used for the identity verification. This module has various sets of commands. They include enroll, verify, identify fingerprints, read or write fingerprint template file. UART interface is used for the communication with external devices. Fingerprint Scanners are used for recognizing and authenticating the fingerprint of an individual.

Dimension (mm): 36 x 21 x 10
Weight: 4.7g

![image](https://user-images.githubusercontent.com/101914547/159106152-97eb0757-fc82-4628-a76d-a08fccb63d29.png)

MICROPHONE-

Noise-cancelling microphones come in different forms and shapes. The most common type is already attached to some kind of headphone or noise- cancelling headset. We are looking for the right one to set for our application.

PRINTER PARTS-

Control panel is used to control the various functions of a printer.
1. Paper Support
2. Sheet feeder
3. Printer cover
4. Output tray
5. Output tray extension
6. CD/DVD guide
7. USB connector
8. Edge guides

![image](https://user-images.githubusercontent.com/101914547/159106187-41399091-606f-4557-9a0f-d75646188a17.png)

KEYBOARD-

Keypad is a combination of set of buttons or arrangement of symbols or alphabetic letters. We can see these keypads in calculators, television remotes etc. It can be simply defined as input device with different set of keys which enables the user to enter their inputs.

![image](https://user-images.githubusercontent.com/101914547/159106225-135d8f94-ad2b-4628-96fd-80e0149b9a4a.png)

POWER SUPPLY-

We are going to use the direct AC supply through a connector, so that when the device is installed will be directly connected to power supply via power ports.
                                       
SOFTWARES USED-

Arduino IDE

Proteus

Fusion 360

Hardware Circuit Diagram or Software Design: 

![image](https://user-images.githubusercontent.com/101914547/159106251-8a13af35-246c-48f3-8f75-18faae3637cd.png)

![image](https://user-images.githubusercontent.com/101914547/159106265-1279fa50-1b2b-4a0f-9275-89fa333b775e.png)

Code:

As printing mechanism is involved with AI based voice assistance only part of the code completed and few other functions must be added to complete the whole together. (For noise clear voice assistance we are using python audi)

Working:

My solution to overcome this problem is here, there will be assistance printing device placed in the banks. Few regarding withdrawals and few regarding deposits. The respective empty column slips will be placed in printing devices. The printing device consists of biometric, when a person want to fill slip, he/she will scan their finger by placing on biometric. After the scan is done, as the device is connected via Wi-Fi to bank database, all the details related to person will be fetched based on fingerprint scanned. After that it assist the person to tell how much amount he/she want to withdraw/deposit.

The voice assistance placed in the device will assist the person in 2 languages i.e English and native language (according to the bank’s location).
The illiterates can take the help of voice assistance for filling the slip where as others can use the keypad for entering the amount. Then all the details will be filled in the respective columns.

IN THE CASE OF DEPOSIT MACHINE:

The deposit machine also consists of one more device that’s not present in withdrawal. In the case of deposit slips, we will be seeing one more column related to denominations. The number of notes of each denomination should be filled, So in that case we will be placing a device which counts the no of notes when the amount is placed in that and accordingly we will be able to fill those columns. All other details are fetched in similar way for both transactions. 
Finally the slip will be printed and person can use it for further process.

FOR WITHDRAWAL

![image](https://user-images.githubusercontent.com/101914547/159106598-497ce9e5-855f-49c9-af23-2c8b1c3f04fc.png)


FOR DEPOSIT

![image](https://user-images.githubusercontent.com/101914547/159106609-eb72577b-1ffc-42f2-82ea-7145be1bd9b1.png)


Practical Implementation & Output:

https://a360.co/3urymSw - the given link will show the real time implementation output. In few more days our physical prototype will be completed.

Existing Competitors:

This is first ever unique solution regarding the filling of slips that are required in bank for any kind of transactions. And our approach for problem is unique in all the ways.

Conclusion:

We have been inspired from the real issue that we faced when we visited a bank. Once we visited a bank for some purpose, and waiting for our call by the manager. During that time almost 30 people came near us for the help to fill the slip. In which most of them are senior citizens and few are illiterates. Then we asked them that why can’t you use ATM machines for money withdrawal? Then they replied that we are not aware of how to use them. In the same way since they are visiting the same bank from many years and using those slips, even then they can’t understand how to fill them and they don’t even understand if we explain them. In order to help them, we have chosen this as our problem statement.

Applications & Future Scope:

We are willing it to implement in all the private and government aided banks especially in rural areas as our target segment of people are senior citizens and illiterates.

During first phase of our project we are completely going to concentrate on withdrawal machine. After the physical prototype implementation in real time is done with accuracy we will be moving on to deposit machine.
