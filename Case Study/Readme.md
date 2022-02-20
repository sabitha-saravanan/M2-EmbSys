## BLOCK DIAGRAM:
![image](https://user-images.githubusercontent.com/98875588/154844185-5cf868d0-5f54-47bf-a947-bea687aaa3c0.png)


Water heating is a heat transfer process that uses an energy source to heat water above its initial temperature. Typically domestic uses of hot water include cooking, cleaning, bathing, and space heating. 
Automatic temperature switch that controls a powerful heater in a hot water storage vessel. The unit is a simple system which could be used for various heating processes at home, offices, etc. The system is an automatic temperature switch that controls a powerful heater in a hot water storage vessel. It has two-fixed temperature settings,
                                        i) Switch the water heater ON and 
                                        ii) Another to switch it OFF

Whenever the temperature of the water reaches the boiling temperature (above 95 degree Celsius) the device automatically switches OFF the electrical power supply to the water-heating element. As the hot water is being drawn from the vessel for use and replaced with cold water or as the water temperature drops below a particular setting (below 85 degree Celsius), the heating element is activated, i.e., turned ON to continue the heating. The switching involves the use of an electromechanical relay. An alarm was incorporated to define the state of the process and it creates awareness when the heated water reaches its maximum preset temperature. It produces an audible sound with the aid of SR latch, an oscillator, and a speaker, which informs the user that the water has reached its optimum boiling. A precision temperature sensor was used in the design for better performance. The design is quite flexible for numerous water heating operations.
                    
Heat was supplied from soldering iron that was pre-heated and placed on the temperature sensor (LM 35) directly, so that it could sense the heat. In less than a minute, there was audible sound from the loudspeaker and the light indicator from the LED flashed as a result of the heat indicating that the temperature has exceeded 95 degree Celsius. The alarm stopped sounding and the LED stopped flashing immediately after the heat was removed. It was also seen that the sensor output increased linearly with increase in temperature. When heat was applied to the sensor, its temperature changes increased the output voltage value of the sensor.

## REQUIREMENTS:

i) HIGH LEVEL REQUIREMENTS:

It is efficient and convenient
They are cost effective
It consume 20% to 30% less energy
When the water is heated it will automatically turn OFF

ii) LOW LEVEL REQUIREMENTS:
 
	Relatively slow heating time
  Susceptible to power outages
	High operating cost

 ## DESIGN:
  
    The approach used in this design is the modular one where the overall design broken into seven functional blocks, 
                                      
•	Temperature sensor unit
•	Comparator unit
•	Input/control latch unit
•	Relay switching unit
•	Alarm unit
•	Power supply unit
•	load

Where each block represents a section of the circuit that carries out a specific function. The functional block diagram shows the interconnection between these blocks.
