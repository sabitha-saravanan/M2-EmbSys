### TABLE OF CONTENT

## 1.INTRODUCTION
## 1.1 ABSTRACT
## 1.2 SWOT ANAYSIS
## 1.3 4W'S AND 1'H

## 2.REQUIREMENTS

 ## 2.1 HIGH LEVEL REQUIREMENTS
 ## 2.2 LOW LEVEL REQUIREMENTS

## 3.ARCHIETECTURE
## 3.1 BEHAVIOURAL DIAGRAM
## 3.2 STRUCTURAL DIAGRAM
## 3.3 COMPONENTS REQUIRED

## 4. FUTURE SCOPE

## 5. CONCULSION

## 1. INTRODUCTION

 Home automation focuses on making it possible for older adults and people with disabilities to remain at home, safe and comfortable. Home automation is becoming a viable option for older adults and people with disabilities who would prefer to stay in the comfort of their homes. Most of the people choose an easy way to reduce the time and effort. Automating the home is the easiest method to reduce the time and effort of the peoples. This system uses voice commands to operate the electrical home appliances. An android application is used to capture the voice commands using Google voice assistant.
The system uses Bluetooth module for transmitting data for controlling the function of electrical loads. The Bluetooth can receive input signal from a device which have Bluetooth compatibility such as smartphone. The smart home automation is most beneficial for handicapped or aged people. The system solve the problem of switching on/off electrical appliances because when user just have to give voice command to control the appliance or electrical loads.
The system is designed in such a way user can control all appliances at once or can control each separately. The system works by interfacing on/off switches of electrical appliance or loads by using mechanical relay or solid state relay, after connecting relays in system the electrical switch works as two way switch. The voice command is sent by using a software designed for controlling the system, a built in microphone and voice recognition system implemented in device. A micro-controller (Arduino Uno) is implemented in system, the micro controller receives input signal from user device and send signal to respective relay for turning on/off electrical appliances connected with system such as bulbs, fan, air conditioner unit etc. It helps those people who are sick, bedridden, physically disabled or elderly to easily operate the home appliances. It will be an easiest method for them to turn on/off the home appliances from where they are. Most people find it difficult and lazy to walk near the switch, to turn on light, fan or any other home appliances.

## 1.1 ABSTRACT

With advancement of Automation technology, life is getting simpler and easier in all aspects. In today’s world, Automatic systems are being preferred over manual system. There is a rapid increase in the number of users of internet over the past decade. This has made internet a part and parcel of life, and IoT is the latest and emerging internet technology. Internet of things is a growing network of everyday object-from industrial machine to consumer goods that can share information and complete tasks with other activities. Wireless Home Automation system using IoT is a system that uses computers or mobile devices to control basic home functions and features automatically through internet from anywhere around the world, an automated home is sometimes called a smart home. It is meant to save the electric power and human energy. The home automation system differs from other system by allowing the user to operate the system from anywhere around the world through internet connection.

## 1.2 SWOT ANALYSIS

![image](https://user-images.githubusercontent.com/98875588/157241542-9ad82d15-c4b7-464b-8e71-2c5bc1229e6a.png)

## STRENGTH

i) With ability to adjust your thermostat and lights with your voice

ii) Gain more control over how much energy your home uses at a given time.

iii) save money and live more cost- effectively

## WEAKNESS

i) Many voice controlled systems are not completely hands free.

ii) Voice control systems that run on mobile devices still require you to press a button on your device before you can issue a command.

## OPPURTUNITIES

i) Home automation allows us to control hosehold electrical applicances like light,door,fan,AC etc.

ii)It also provides home security and emergency system to be activated.

## THREATS

i) According to rambus a premier silicon intellectual property and chip provider,an estimated 80% of internet of things devices are vulnerable to one of the many attack scenarios.

ii) These devices for the most part, present very little security risk when used as stand-alone devices and not connected to the internet.

iii) These stand-alone devices introduce numerous cyber security risks.

## 1.3 4W'S & 1H

![image](https://user-images.githubusercontent.com/98875588/157240229-49637612-c5c6-49d0-873c-ed4c4728d348.png)

## WHO 
Home automation can be used by all age group people.

## WHAT

Home automation gives access to control devices in your home from a mobile devices anywhere.

## WHEN

It can be used anytime

## WHERE

It can be working only you are connected the bluetooth to AMR voice device

## HOW

First you need to install the AMR voice app,next choose bluetooth option and connect robot after successful connection the device are ready to transmit data. Next press the microphone icon on AMR voice app and start giving commands.

## 2.REQUIREMENTS

## High level requirements

|ID|Description|status|
|---|---|---|
|HR01| Motion detection in all system area.|Implemented|
|HR02| Auto call user when system hacked.|Implemented|
|HR03| Customize your needs.|Implemented|
|HR04| It keeps home secure by being able to look front door smart phone or tablet.|Implemented|

## Low level requirements

|ID|Description|Status|
|---|---|---|
|LR01|Depending upon the complexity of the system, installing a home automation device can be a significant burden on the homeowner.|Implemented|
|LR02|controlling all aspects of home automation from one centralized platform is important, but not at all systems are compatible with on another.|Implemented|
|LR03|As with all computing devices, security will becoe a greater issue as more people use smart home devices.|Implemented|
|LR04|At a specific time give only one command|Implemented|

## 2.ARCHITECTURE

### 2.1 BEHAVIORAL DIAGRAM
![image](https://user-images.githubusercontent.com/98875588/155729187-efece4ca-0139-4aa4-8914-64e1fe258d0b.png)

### 2.2 STRUCTURAL DIAGRAM
![image](https://user-images.githubusercontent.com/98875588/155729281-7da029a3-bf1a-44d7-b2ba-94483b0d6bda.png)

## 3.3 COMPONENT REQUIREMENTS:

## 3.3.1 Arduino UNO  

 i) Arduino is an open-source electronics platform based on easy-to-use hardware and software. Arduino boards are able to read inputs - light on a sensor, a finger on a button, or a Twitter message - and turn it into an output - activating a motor, turning on an LED, publishing something online. There are many other microcontrollers and microcontroller platforms available for physical computing
 
 ii) The Arduino Uno contains asset of analog and digital pins that are input and output pins which are used to connect the board to other components. The boar has 14 digital I/O pins (six capable of PWM output), 6 analog I/O pins, and is programmable with Arduino IDE (Integrated Development Environment).The board has a USB connection that can be used to a power supply to the board. The board is used for electronics projects and used to design circuit. Arduino Uno is a low cost, flexible, and easy to use programmable open source microcontroller board that can be integrated into a variety of electronics projects.
 
   ![image](https://user-images.githubusercontent.com/98875588/155744067-78e3d9c5-fc63-4c5d-9931-717bc23deab2.png)

 ## 3.3.2 HC-05 Bluetooth module
 
 i) HC-Bluetooth module is an easy to use Bluetooth Serial port protocol (SPP) module, designed for transparent wireless serial connection setup .It provides switching between master and slave mode which means it is able to use neither receiving nor transmitting data. It uses 2.45GHZ frequency band .The transfer rate of the data can vary up to 1Mbps and it is in range of 10 meters.
 
 ii) The HC-05 module can be operated within 4-6V of power supply. Designed to replace cable connections to communicate with the electronics.Usually, it is used to connect small devices like mobiles using a short range of wireless connection to exchange files.This module works on 3.3 V. We can connect 5V supply voltage as well since the module has on board 5 to 3.3 V regulator.
 
   ![image](https://user-images.githubusercontent.com/98875588/155744157-51372a05-39f3-444c-9aa6-f08a502746c1.png)

 ## 3.3.3 2N2222 Transistor
 
  i) The 2N2222 is a common NPN bipolar junction transistors (BJT) used for general purpose low-power amplifying or switching applications. It is designed for low to medium current, low power, medium voltage, and can operate at moderately high speeds. The 2N2222 transistors is made of either germanium or silicon that has been saturated with either a positively or negatively changed material process called as doping. 
  
 ii) The 2N2222 has a positively charged section between two negatively charged sections. The resulting two connections between the three sections are where the 2N2222 derives the name bipolar junction transistors. The materials used are arranged in the order of negative, positive, then so the devices is also said to be NPN transistors. 
              
   ![image](https://user-images.githubusercontent.com/98875588/155744290-0148d0d7-61f2-4a43-a2d5-7f067fbd1eff.png)
   
## 3.3.4 LCD Display 

The term LCD is a Liquid Crstal display.A 16x2 LCD means it can display 16 characters per line and there are 2 lines.In this LCD each character is displayed in 5x7 pixel matrix.The 16x2 intelligent alphanumeric dot matrix display is capable of displaying 224 different characters and symbols.It has 6 columns and 2 rows.These displays are mainly preffered for multi segment light emitting diodes and seven segments.The main benefits of using this module are inexpensive, simply programmable, animations, and there are no limitations for displaying custom characters,special,and even animations,etc..

![lcd-16x2-pin-diagram](https://user-images.githubusercontent.com/98875588/157200446-a651e826-468e-4d00-93eb-86cdf60cfb30.jpg)

## 4.FUTURE SCOPE

Future scope for the home automation systems involves making homes even smarter.Homes can be interfaced with sensors including motion sensors, light sensors, and temperature sensors, and provide automated toggling of devices based on conditions.Internet of things can also be controlled home automation system. We can replace bluetooth by GSM modem so that can achieve device controlling by sending SMS using GSM modem. Home of future is a space for the digital natives. With the invention of lots of automation technologies featuring IOT and AI home automtaion, has become a reality.

## 5.CONCULSION

The home automation system has been experimentally proven to work satisfactorily by connecting sample appliances were successfully controlled from a wireless mobile device .The system as the name indicates, “Home Automation” makes the system more flexible and provides attractive user interface compared to other home automation. The Bluetooth client was successfully tested on a multitude of different mobile phones from different manufacturers, thus proving is portability and wide compatibility. Thus a low-cost home automation system was successfully designed, implemented and tested. The home automation using internet of things has been experimentally proven to work satisfactorily by connecting simple appliances to it and the appliances were successfully controlled remotely through internet. The designed system not only monitors the sensor data, like temperature, gas, light, motion sensors, but also actuates a process according to the requirement, for example switching on the light when it gets dark. It also stores the sensor parameters in the cloud in a timely manner. This will help the user to analyze the condition of various parameters in the home anytime anywhere. Hence this project conclude that the required goals and objectives of home automation system have been achieved. The system design and architecture were discussed, and prototype presents that the basic level of home appliance has been implemented.

