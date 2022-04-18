# Smart Water Purity System
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

## Description
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
Water is the source of life for the humans. The quality of the water is very important, as it will affect the human life's. The water purity is something which this project is based on. The Smart Water Purity System, shows the amount of water that is pure and impure. Through this we can know the purity of any water that is avaliable.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Identifying Features
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* The purity of the water.
* The impurity of the water.
* The percentage of of Pure and Impure in the Water.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### State of art / Research
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Pollution of water is one of the main threats in recent times as drinking water is getting contaminated and polluted. To make certain the supply of pure water, the quality of the water should be examined first. Smart solutions for monitoring of water purity are getting more and more significant these days with innovation in sensors, communication, and Internet of Things (IoT) technology. 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 5 W's 1 H
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![5W 1H](https://user-images.githubusercontent.com/98872937/157225727-55c6979f-b698-4b78-9c26-e712762bf092.jpg)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

## SWOT Analysis
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![SWOT Analysis](https://user-images.githubusercontent.com/98872937/157233492-eae5496b-7d60-4185-89db-af6ecd9c0f89.jpg)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

## High Level Requirements
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

| ID | High Level Requirements |
|---------- | --------------- |
| HL1 | The purity of water shall be found |
| HL2 | The impure percentage of water shall be found |
| HL3 | System shall detect the amount of drinkable water |
| HL4 | The system shall display both Pure and Impure Water |

## Low Level Requirements
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

| ID | Low Level Requirements |
|---------- | --------------- |
| LL1 | The amount of water that is good |
| LL2 | Based on good water the bad water is calculated |

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Best Method followed 
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
* The people will find out the purity of water that they use in everyday life.
* The impure water could then be sent for purification. 
* The amount of pure water in our day to day life.

# Block Diagram and Blocks Explaination
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Block Diagram
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![Block Diagram](https://user-images.githubusercontent.com/98872937/157183542-9c5f32e8-a323-48c8-b796-510cb3d93d21.jpg) 

Blocks Explaination
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Atemga 328 Microcontroller - 
* The ATmega328 is a single-chip microcontroller. 
* ATmega328 is an Advanced Virtual RISC (AVR) microcontroller. 
* It supports 8-bit data processing. ATmega-328 has 32KB internal flash memory.
* It has an EEPROM memory of 1KB and its SRAM memory is 2KB. 

### Potentiometer as Sensor - 
* A potentiometer sensor measures the quality of the water in percentage and converts it into an electrical signal.
* Potentiometer Sensors detect the position of something which means that they are referenced either to or from some fixed point or position. 
* These types of sensors provide a “positional” feedback.
* The potentiometer is used because it is an inexpensive and easy to use position sensor. 

### Actuator ( Switch ) - 
* An actuator is a device that alters the physical quantity as it can cause a mechanical component to move after getting some input from the sensor.
* The control signal comes from a microcontroller programmed by software. 
* It receives control input (generally in the form of the electrical signal).
* It generates a change in the physical system through producing force, heat, motion, etc. 

### LCD Display - 
* A liquid crystal display, better known as an LCD, is an excellent way for a microcontroller to present visible information. 
* Most include sophisticated electronics that accept data and convert the data to letters, numbers, and symbols that appear on the display. 
* LCDs can display output from the microcontroller that has been asked by the user. 

### LED Bulb - 
* The LEDs are simple electronic display units available.
* It is mostly used for indication purposes. 
* It is used widely as indicator during test for checking the validity of results at different stages.
* It is very cheap and easily available in variety of shape, color and size. 

### Resister - 
* A Resistor is a passive two-terminal electrical component that implements electrical resistance as a circuit element.
* Resistors are used to reduce current flow, adjust signal levels, to divide voltages, bias active elements, and terminate transmission lines. 

### Voltage Source - 
* It is a voltage source that supplies fixed amount volatge ( 5V ) to the microcontroller. 

# Architecture
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

Flowchart
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Flowchart](https://user-images.githubusercontent.com/98872937/157205724-60a6339e-1189-4457-b37d-00daa75069ae.jpg) 

TEST PLAN
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

HIGH LEVEL TEST PLAN
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

| Test ID | Description | Exp I/P | Exp O/P | Actual Output | Passed or Not |
|---------|-------------|---------|---------|---------------|---------------|
| HL01 | Check if the code is working as expected | Valid Input | Correct Output | Correct Output | Passed |
| HL02 | Check if the system works when no power is given | No Power | Switch Off | Switch Off | Passed |
| HL03 | Check if the system works when power is given | Power | Switch On | Switch On | Passed |
| HL04 | Check if the LED glows when the switch is Off | Switch Off | No LED Glows | No LED Glows | Passed |
| HL05 | Check if the Actuator works when the Sensor is On | Sensor On | Correct Output | Correct Output | Passed | 

LOW LEVEL TEST PLAN
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
| Test ID | Description | Exp I/P | Exp O/P | Actual Output | Passed or Not |
|---------|-------------|---------|---------|---------------|---------------| 
| LL01 | The amount of Pure Water | Water to the Sensor | Displays as P% | Displays as P% | Passed |
| LL02 | The amount of Impure Water | Water to the Sensor | Displays as I% | Displays as I% | Passed |
| LL03 | The LED glows when data is sent from the sensor | Information sent | LED Glows | LED Glows | Passed | 
| LL04 | The LED doesn't glow when the actuator is Off | Actuator Off | LED doesn't glow | LED doesn't glow | Passed |
| LL05 | When volt source is Off | No Voltage | Off | Off | Passed | 

Applications
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Water Utilities

Water suppliers and utilities need to ensure the supply of the high purity water that the consumers can use for drinking and other purposes. 
By implementing this project, the utilities can monitor the quality of the distributed water in overhead tanks and even in pipelines. 

### Agriculture:

Optimum water quality is a pre-requisite for high yield of crop production. Based on the crop to be cultivated, the sensors and probes can be used to identify impurities that can hamper its growth. This will help farmers to enhance their irrigation practices and ensure a high yield of healthy crops.

### Manufacturing Units:

Production and manufacturing-based companies often discharge chemicals and other harmful fluids in rivers. Strict regulations are hence imposed on them to make sure that no harm is made to the aquatic life. Factories can hence use real-time water purity system to make sure that compliance is conformed as per the imposed regulations.

### Aquaculture

Aquaculture refers to the breeding of aquatic organisms like fishes, under a controlled environment. Purity of water plays an essential role in facilitating the growth of healthy fishes and crustaceans in large numbers so that they can be used as a livestock. 

### Wastewater Treatment

Wastewater generated is to be treated and managed before it is discharged into a freshwater body. Parameters like temperature, turbidity, and TDS are hence to be monitored to make sure that the water is treated properly before it is secreted. Smart water quality monitoring system using IoT optimize the inspection processes and hence reduce the need for manual interference. 









