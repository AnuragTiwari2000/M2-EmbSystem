# WATER TANK CONTROLLER WITH QUALITY CHECK

# TABLES OF CONTENTS

1. [Introduction](#introduction)

   1.1. [ABSTRACT](#abstract)

   1.2. [OBJECTIVE](#objective)
   
2. [Requriments](#requriments)
   
   2.1. [High Level Requriment](#high-level-requriment)
   
   2.2. [Low Level Requriment](#low-level-requriment)

   2.3. [SWOT ANALYSIS](#swot-analysis)

   2.4. [5W'S 1H](#5w's-1h)

3. [BLOCK DIAGRAM AND COMPONENTS](#block-diagram-and-components)

   3.1. [BLOCK DIAGRAM](#block-diagram)

   3.2. [COMPONENT DESCRIPTION](#component-description)

4. [ARCHITECTURE](#architecture)
   
   4.1. [BEHAVIOURAL DIAGRAMS](#behavioural-diagrams)
         
        4.1.1. [HIGH LEVEL](#high-level)
         
        4.1.2. [LOW LEVEL](#low-level)
   
   4.2. [STRUCTURAL DIAGRAMS](#structural-diagram)

         4.2.1. [HIGH LEVEL](#high-level)

         4.2.2. [LOW LEVEL](low-level)

 5. [APPLICATIONS](#applications)
 
 # 1.INTRODUCTION

 ## 1.1ABSTRACT
 Water tank controller with Quality check is a system that shall be used to refill water tanks in houses and commercial buildings and monitor the water quality as well. This helps in elimination of manual monitoring and refilling of water tanks. The major advantages of the system is that it helps in automating tasks and also there is no wastage of water overflowing from tanks. It also provides the facility to check water quality as well. The components used in the system is very simple which makes the product economically accessible as well. The overall system development phase is explained.

 ## 1.2 OBJECTIVE
 * To refill the water tank automatically without any wastage of water and power.
 * To monitor the quality of water and alert the user.
 
 # 2.REQUIREMENT
 
 ### 2.1 High Level Requirements:

ID     | Description
-------| -----------------------------------------
HLR 1  |To Refill the water tank automatically when tank becomes empty.
HLR 2  |Alert the user when the tank is filled.
HLR 3  |To check the quality of water and alert user.
HLR 4  |To turn ON the motor when the tank becomes empty.

### 2.2 Low Level Requirements:


ID     | Description
-------| -----------------------------------------
LLR 1  |A Microcontroller is used for controlling the process.
LLR 1.1  |A water level sensor is used to check the water level.
LLR 2  |Buzzer is used to alert the user.
LLR 3  |A water Quality sensor is used to chechk the quality of the water
LLR 4  |A Motor Driver shall be used to switch ON the motor.
