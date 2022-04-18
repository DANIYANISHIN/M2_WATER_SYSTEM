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

