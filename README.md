# I2C-MASTER-Led-On-Off-With-Button-States
 Turning STM32 LED On/Off according to button with I2C Communication
//////////////////////////////////////////////////////////////////
In order to make 2 debugs at the same time: 
*Two separate workspaces must be opened.
*Debugger must be in OCD mode.
*Debug.cfg files must adjusted with STM32 card's serial ID.

--------------- SLAVE IOC ----------------

PB7 	- 	I2C1 SDA	*GPIO PULL UP MODE*
PB6 	- 	I2C1 SCL	*GPIO PULL UP MODE*

PD14 	- 	GPIO OUTPUT / RED LED

PH12	-	CRYSTAL/CERAMIC RESONATOR
PH13	-	CRYSTAL/CERAMIC RESONATOR

I2C1 EVENT AND ERROR INTERRUPTS ARE ENABLED.
CLOCK CONFIG IS DEFAULT.

--------------- MASTER IOC ----------------

PB7 	- 	I2C1 SDA	*GPIO PULL UP MODE*
PB6 	- 	I2C1 SCL	*GPIO PULL UP MODE*

PA0 	- 	GPIO INPUT / BUTTON

PH12	-	CRYSTAL/CERAMIC RESONATOR
PH13	-	CRYSTAL/CERAMIC RESONATOR

I2C1 EVENT AND ERROR INTERRUPTS ARE ENABLED.
CLOCK CONFIG IS DEFAULT.
