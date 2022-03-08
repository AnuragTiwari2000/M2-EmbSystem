# WATER TANK CONTROLLER

# TABLES OF CONTENTS

1 [INTRODUCTION](#1-introduction)

   1.1. [ABSTRACT](#11-abstract)

   1.2. [OBJECTIVE](#12-objective)
   
2 [REQUIREMENTS](#2-requriments)
   
   2.1. [High Level Requriments](#21-high-level-requriments)
   
   2.2. [Low Level Requriments](#22-low-level-requriments)

   2.3. [SWOT ANALYSIS](#23-swot-analysis)

   2.4. [5W'S 1H](#24-5w's-1h)

3 [BLOCK DIAGRAM AND COMPONENTS DESCRIPTION](#3-block-diagram-and-components)

   3.1. [BLOCK DIAGRAM](#31-block-diagram)

   3.2. [COMPONENTS DESCRIPTION](#32-components-description)

4 [ARCHITECTURE](#architecture)
   
   4.1. [BEHAVIOURAL DIAGRAMS](#41-behavioural-diagrams)
         
      4.1.1. [HIGH LEVEL BEHAVIOURAL DIAGRAM](#411-high-level-behavioural-diagram)
         
      4.1.2. [LOW LEVEL BEHAVIORAL DIAGRAM](#412-low-level-behavioural-diagram)
   
   4.2. [STRUCTURAL DIAGRAMS](#42-structural-diagrams)

      4.2.1. [HIGH LEVEL STRUCTURAL DIAGRAM](#421-high-level-stryctural-diagram)

      4.2.2. [LOW LEVEL STRUCTURAL DIAGRAM](#422-low-level-structural-diagram)

 5 [APPLICATIONS](#5-applications)
 
 # 1.INTRODUCTION

 ## 1.1 ABSTRACT
 Water tank controller with Quality check is a system that shall be used to refill water tanks in houses and commercial buildings and monitor the water quality as well. This helps in elimination of manual monitoring and refilling of water tanks. The major advantages of the system is that it helps in automating tasks and also there is no wastage of water overflowing from tanks. Level control is one of the most important applications in chemical process industries, food beverages industries, pharmaceutical industries,
nuclear power generation plants etc. It also provides the facility to check water quality as well. Water quality affects the aquatic life and influence the human health, so water quality monitoring is crucial.  The components used in the system is very simple which makes the product economically accessible as well. The overall system development phase is explained.

 ## 1.2 OBJECTIVE
 * To refill the water tank automatically without any wastage of water and power.
 * To monitor the quality of water and alert the user.
 
 # 2.REQUIREMENTS
 
 ## 2.1 High Level Requirements:

ID     | Description
-------| -----------------------------------------
HLR 1  |To Refill the water tank automatically when tank becomes empty.
HLR 2  |Alert the user when the tank is filled.
HLR 3  |To turn OFF the motor when the tank is full
HLR 4  |To turn ON the motor when the tank becomes empty.

## 2.2 Low Level Requirements:


ID     | Description
-------| -----------------------------------------
LLR 1  |A Microcontroller is used for controlling the process.
LLR 2  |A water level sensor is used to check the water level.
LLR 3  |It shall Turn on Motor when Water Tank is empty.
LLR 4  |It shall Turn off Motor when Water Tank is Full.
LLR 4  |A Motor Driver shall be used to switch ON the motor.

## 2.3 SWOT ANALYSIS

### STRENGTH

  * Automation
  * Wastage of water is eliminated.
  * Water quality is maintained
  * Less power consumption.

### WEAKNESS

  * Can be damaged by external factors.
  * Sensors need frequents cleaning.
  * If the Ardunio gets reset the system will not work.

### OPPURTUNITIES

  * Adopting to new technology.
  * Automation can be achieved.
  * Since now a days water usage is increassing so much it is very important to save the water so this kind of systems are required.
### THREATS

  * External Damage.
  * Theft

## 2.4 5W'S 1H

### WHAT
   This a controller that helps to automaticlly refill the water tank using sensors and micro controller.
### WHEN
   It is used when we need to fill water to the pressure tank.
### WHERE
   It can be used in domestic,Industrial as well as Commercial complexes.
### WHO
   Normal consumers are the people who use this.
### WHY
   Inorder to refill water to the tank without wastage.
### HOW
   By using a micro-controller, sensors and few actuators.
   
# 3. BLOCK DIAGRAM & COMPONENTS DESCRIPTION

## 3.1 BLOCK DIAGRAM

![image](https://user-images.githubusercontent.com/98815562/157077804-9ee61ebf-3e93-4d05-bfbe-efda99916643.png)

## 3.2 COMPONENTS DESCRIPTION

### Arduino
     Arduino is a one type of micro controller circuit ATmega328P. The programme is carried out in the arduino by using the arduino software in the programming languages like C      and C++ .
### SENSORS
#### Water level sensor
    The ultrasonic sensor is a non contact type device which uses the sound waves. There are 2 ports on the front, one port generates the ultrasonic waves like a micro speaker        and other port receivers. The ultrasonic waves like a small micro phone. The liquid level is calculated, on the basis of the total time required for the sound to reflect
     back.

### ACTUATORS

#### Motor Driver Circuit
    * Motor Driver circuit is used to switch on and off the based upon the signals received from the sensors.
    * Pump is a mechanical device which converts the mechanical energy into the pressure energy. It creates the partial vacuum in the suction side and sucks the liquid which is       delivered with high pressure at a required height.

#### LED’s
    Shows the status of motor wether it is on or off.

### Power Supply
     AC power supply is converted to DC and given to the circuit in order to run it.
     
### Resistors
     to protect LED and complete the circuit.
     
# 4.ARCHITECTURE

## 4.1 BEHAVIOURAL DIAGRAMS

### 4.1.1 HIGH LEVEL BEHAVIOURAL DIAGRAM

![HIGH LEVEL](https://user-images.githubusercontent.com/98815562/155871590-bd805006-668d-470c-b722-aff56ff43e8f.png)

### 4.1.2 LOW LEVEL BEHAVIOURAL DIAGRAM

![LOW LEVEL](https://user-images.githubusercontent.com/98815562/155871625-8b8a5161-09f7-42a5-9650-374fd5274952.png)

## 4.2 STRUCTURAL DIAGRAMS

### 4.2.1 HIGH LEVEL STRUCTURAL DIAGRAM

![HIGH LEVEL](https://user-images.githubusercontent.com/98815562/155871676-56d668e8-d931-49cf-9be5-e3ae46af8d35.png)

### 4.2.2 LOW LEVEL STRUCTURAL DIAGRAM

![LOW LEVEL](https://user-images.githubusercontent.com/98815562/155871682-040c1e9a-2aa3-4144-834e-76bd9ea63c4c.png)

### FLOW CHART

![image](https://user-images.githubusercontent.com/98815562/157078743-347a11ec-1a17-4b9d-99cd-5ff0b5572413.png)

# IMAGES OF SIMULATION

## When water tank is full

![Screenshot (171)](https://user-images.githubusercontent.com/98815562/157210822-d4a39642-cc64-46ac-bc1d-908a3f8fa06a.png)

## When capacity of water tank is at less than 10%

![Screenshot (172)](https://user-images.githubusercontent.com/98815562/157211082-42447048-7c71-499c-8587-fddfe7903423.png)

## When capacity of water tank is at less than 30%

![Screenshot (173)](https://user-images.githubusercontent.com/98815562/157211452-371f8641-5ddf-407f-98a8-2d557cd851e8.png)

## When capacity of water tank is at less than 50%

![Screenshot (174)](https://user-images.githubusercontent.com/98815562/157211524-8e294f02-aa08-4e0f-97fb-2b43c590074f.png)

## When capacity of water tank is at less than 80%

![Screenshot (175)](https://user-images.githubusercontent.com/98815562/157211588-fef2cf9e-bb74-4d3d-807f-60ce54bbb4f4.png)

## When capacity of water tank is at less than 100%

![Screenshot (176)](https://user-images.githubusercontent.com/98815562/157211633-cf8a0294-bff3-446b-90b3-15a16bd88469.png)


# 5.APPLICATIONS
  * Houses
  * Industries
  * Schools
  * Hospitals
  * Commercial complexes





