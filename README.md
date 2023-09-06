# Giving-a-Chance-to-e-Dice
Here is my electronic Dice which gives a random output. The input is taken as noise from the vibration sensor.
Playing different games are the best part of childhood. We all remember the Ludo and snake ladder game. Which is a multiplayer dice game. It is most popular indoor games among children. The dice number help to move the cap from one position to another and it is totally random. No one can’t predict the next move or what will be the next number on dice. Keeping that in mind I searched an electronic dice kit on internet and I found the one. It contains a random number generator program and finally display the output on LEDs.

![My Video](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/c61c8f57-6d17-4387-94ef-dd3a80ecae77)


If you are looking for an easy way to get started with soldering or simply want to make a small portable gadget, this set is a great opportunity. “LED cube” is an educational set for learning the soldering skill, with which you get a small electronic game at the end. After you turn on and shake this board, certain LEDs will light up randomly and symbolize the number, as if a real die had been thrown. Sponsored by JLCPCB: https://jlcpcb.com/?from=SSA

How random number generator works:

Usually by own a microcontroller cannot generate the exact random number. We have to give an initial position or hint which can be any type of analog signal, noise or may be the time input. Which microcontroller then process and convert into numbers, manipulate the data and arrange the numbers within the given range. Then display on the LED or LCD.

Kit components:

![mini_IMG_8482](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/6f2886b0-5c8e-4926-a6c8-b448f132cd39)

PCB / Custom PCB
https://jlcpcb.com/?from=SSA

Attiny404 microcontroller

7 LEDs

7 330ohm resistors

1 10kohm resistor

Battery holder

CR2032 battery

Switch

Vibration sensor SW-18020P

Keychain ring

Buy link: https://soldered.com/product/led-dice-solder-kit/

Microcontroller used:

![mini_IMG_8484](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/4c4b1553-21f9-4798-902d-486a94a83777)

It is based on the Attiny404 microcontroller, programmed in Arduino, and there is a battery on the back which makes this gadget portable. Attiny404 is 8-bit microcontroller unit comes with internal 16Mhz clock and 32.768 low power mode. It has 4KB flash, 256B SRAM and comes in 14 pin DIP SMD package. There is also a keychain so you can always carry your new game with you! Soldering is easy according to the markings on the board. Get more info about the microcontroller and interfacing protocols from here.

Working:

![My Video4](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/9945c8b5-4bec-4760-90f6-84be91b7b757)

Here the input is taken in the form of noise from vibration sensor then it is given to the microcontroller for further processing and noise value is always different every time that’s why it works always in random manner.

![mini_IMG_8504](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/040f449d-9365-4893-95e4-3559a5141b57)

This kit comes with already programmed microcontroller so no need to change any settings like burning bootloader, flashing etc. This is a standalone project, you may consider my own made Led based E-dice shared below using Arduino.

Soldering guide:

![mini_IMG_8491](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/28827453-c31a-47c4-84e8-0a4bbf64522b)

Soldering the PCB is very simple just place the given component as given in the soldering guide. And solder them properly make sure that every connection is made properly because anu dry connection may produce undesirable output behaviour. You may consider this soldering guide before making connections.

You can order your Custom PCB from JLCPCB, 5pcs of 2-layer PCB in just $2. You can explore the more services like PCBA, SMT assembly, high precision PCB, Flex PCB, 3D printing, RF PCB, Stencil and CNC machine parts.

My homemade dice:

![ice_screenshot_20230713-174958](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/5737699c-6815-41c4-8cfa-922b18d9e53c)

You can make the same with simple piece of Pref-board or using breadboard using Arduino and LEDs. The code is very simple, you have to press a tactile button connected to Arduino. Which randomly will light up the LEDs. The code and schematics for this is given below.

![My Video](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/dc175d76-b0e4-4f66-993e-8f5349b3a7d5)

PCB Design:

![ice_screenshot_20230713-180908](https://github.com/electroboy001/Giving-a-Chance-to-e-Dice/assets/97245507/6a616279-dc68-47e5-84f9-9b511ea22951)

Here I made a small shield using the schematics, if you want to use my design then download from here. This PCB design is according to the pins defined in the program. Flashing the code in Arduino is quite simple just connect the board to PC, open Arduino IDE and choose the right board/COM port from tools and hit upload. This design has one Battery header back side where you can connect a battery u pto 9volts. You can try JLCPCB for 5pcs of 2-layer PCB in just $2. Sign-up using this link to JLCPCB and get free PCB coupons of worth $54.
https://jlcpcb.com/?from=SSA
