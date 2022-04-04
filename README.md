# Game-Controls-Through-Gesture
Make a Game Controls Through Gesture using Arduino Leonardo, FLEX Sensor, ADEXL 335, Jumper Wire, Breadboard


 Ground or GND is where the electrical level is at 0 Volts. It is mostly used as reference to all other electronic parts, they need one common point to operate correclty and that is usually GND

 VCC (Voltage Common Collector)

 Arduino Leonardo = 
					Leonardo is different from other Arduino boards because it has a microcontroller with inbuilt USB 2.0 communication.
 					

 					1. Input voltage: 7V-12V

					2. Operating voltage: 2.7V-5.5V
					
					3. 12 analogue input pins and seven pulse-width-modulated (PWM) outputs

					4. 32kB flash memory

					5. 1kB EEPROM

					6. 2.5kB SRAM

					7. 40mA per I/O pin current (DC)


FLEX Sensor = 
        The Flex Sensor patented technology is based on resistive carbon
				elements.  FLEX sensor converts flex angle to RESISTANCE parameter.
				RESISTANCE parameter to VOLTAGE parameter. For that we are use VOLTAGE DIVIDER circuit(56K Ohms Resistor).

				PinNo	Description
				P1 		Usually connected to positive of power source.
				P2 		Usually connected to ground.

				FLEX SENSOR Features and Specifications
				Operating  voltage of FLEX SENSOR: 0-5V
				Can operate on LOW voltages
				Power rating : 0.5Watt (continuous), 1 Watt (peak)
				Life: 1 million
				Operating temperature: -45ºC to +80ºC
				Flat Resistance: 25K Ω
				Resistance Tolerance: ±30%
				Bend Resistance Range: 45K to 125K Ohms(depending on bend)


				How to Use FLEX SENSOR
				FLEX SENSOR is basically a VARIABLE RESISTOR whose terminal resistance increases when the sensor is bent. So this sensor resistance increases depends on                surface linearity. So it is usually used to sense the changes in linearity.

				surface of flex sensor is linear = nominal resistance
				surface of flex sensor is bent 45º angle = resistance increases to twice as before
				surface of flex sensor is bent 90º angle = resistance could go as high as four times the 											nominal resistance

ADEXL 335 = 

	The ADXL335 is a small, low power, complete 3-axis accelerometer with signal conditioned voltage outputs. It can measure the static acceleration of gravity in tilt-sensing applications, as well as dynamic acceleration resulting from motion, shock, or vibration.ADXL335 IC this module also consists of a 3.3V voltage regulator IC.  


	ADXL335 Pinout

	Pin Name		Description
	VCC    			The Vcc pin powers the module, typically with +5V
	GND 			Power Supply Ground
	X 				X-axis Analog Output Pin
	Y 				Y-axis Analog Output Pin
	Z 				Z-axis Analog Output Pin
	ST 				Self-Test Pin. This pin controls the Self-Test feature.

	Accelerometer Module Features & Specifications
	Operating Voltage: 3V to 6V DC
	Operating Current: 350μA
	Sensing Range: ±3g
	3-axis sensing
	High Sensitivity for small movements
	Needs no external components
	Easy to use with Microcontrollers or even with normal Digital/Analog IC
	Small, cheap and easily available

Jumper Wire = 
			A jump wire is an electrical wire or group of them in a cable with a connector or pin at each end. Wires are used to connect components to each other on the breadboard or other prototypes, internally or with other equipment or components, without soldering.
			
			Jumper wires typically come in three versions: male-to-male, male-to-female and 
			female-to-female.

			 The difference between each is in the end point of the wire
			 Male ends have a pin protruding and can plug into things
			 female ends do not and are used to plug things into
			  Male-to-male jumper wires are the most common.Male-to-male jumper wires are the most common



 
 Breadboard =
 
			A breadboard is a widely used tool to design and test circuit. You do not need to solder wires and components to make a circuit while using a bread board. It is easier to mount components & reuse them. Since, components are not soldered you can change your circuit design at any point without any hassle. It consist of an array of conductive metal clips encased in a box made of white ABS plastic, where each clip is insulated with another clips. There are a number of holes on the plastic box, arranged in a particular fashion. 

 	 	there are different kinds of breadboards:-"full-size," "half-size," and "mini" breadboards

			 A typical bread board layout consists of two types of region also called strips. Bus strips and socket strips. Bus strips are usually used to provide power supply to the circuit. It consists of two columns, one for power voltage and other for ground.in full size breadboard bus strip divide into 2 part.and each part have a 5 substitute with 6X2 matrix size.
			  Socket strips are used to hold most of the components in a circuit. Generally it consists of two sections each with 5 rows and 64 columns. Every column is electrically connected from inside.
