## HIGH LEVEL TEST PLAN
|**SLNO**|**Test ID**|**Testing Function**|**Expected Input**|**Expected Output**|
| :- | :- | :- | :- | :- |
| 1 | HLR1 | Wiper Control Module | When moisture sensor senses the water, it sends signal to wiper shield to turn on | Wiper shield will work properly |
| 2 | HLR2 | Interior Light Control Module | Any kind of motion detected in the PIR Motion Sensor (for example when the door is open) | The interior lighting will work properly |
| 3 | HLR3 | Adaptive light Control Module | LDR sensor sense the presence and absence of light is necessary | Turn on/off street lights when needed |
| 4 | HLR4 | Car Reverse Gear Buzzer | Car Reverse Radar Sensor detect the objects during reversing the vehicle and sends signal to buzzer | Buzzer starts beeping when the person in vehicle  uses reverse gear |


## LOW LEVEL TEST PLAN
|**SLNO**|**Test ID**|**Testing Function**|**Expected Input**|**Expected Output**|
| :- | :- | :- | :- | :- |
| 1 | HLR1-LLR1 | Wiper Control Module | When the input is 1 i.e. When the moisture sensor senses the water | The green LED will glow i.e. the GPIO pin with PORT D 12 will be set |
| 2 | HLR1-LLR2 | Wiper Control Module | When the input is 0 i.e. When no water is detected from moisture sensor | The green LED will stop i.e. the GPIO pin with PORT D 12 will be reset |
| 3 | HLR2-LLR1 | Interior Light Control Module | When the input Is 1 i.e. when the motion is detected | The green LED will glow i.e. the GPIO pin with PORT D 12 will be set |
| 4 | HLR2-LLR2 | Interior Light Control Module | When the input Is 0 i.e. when no motion is detected | The green LED will stop i.e. the GPIO pin with PORT D 12 will be reset |
| 5 | HLR3-LLR1 | Adaptive light Control Module | When the input is 1 i.e.  When the darkness is detected around | The green LED will glow i.e. the GPIO pin with PORT D 12 will be set |
| 6 | HLR3-LLR2 | Adaptive light Control Module | When the input is 0 i.e.  When the lights are detected around | The green LED will stop i.e. the GPIO pin with PORT D 12 will be reset |
| 7 | HLR4-LLR1 | Car Reverse Gear Buzzer | When the input is 1 i.e.  When the person in a vehicle uses reverse gear | The green LED will glow i.e. the GPIO pin with PORT D 12 will be set |
| 8 | HLR4-LLR2 | Car Reverse Gear Buzzer | When the input is 0 i.e.  When  the reverse gear is not in use | The green LED will stop i.e. the GPIO pin with PORT D 12 will be reset |
