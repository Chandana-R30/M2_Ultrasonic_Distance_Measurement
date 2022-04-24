#### Ultrasonic Distance Measurement System

# Problem Statement:
A low cost distance measurement system using ultrasonic sensor which works good in different light condition and has the capability to detect the  distance and hence
location of the object.

## Introduction

Distance measurement using HC-SR04 and ATMEGA328p. The developed project is used to measure distance in centimetres, with the help of HC-SR04 Ultrasounic sensor, ATMEGA328 microcontroller, LCD Display via the I2C bus. The usage of ultrasonic sensor is an advantage of this system. It has only four pins namely VCC (Power), Trig (Trigger), Echo (Receive), and GND (Ground). This feature makes it easy to set up ans use for my distance-finding project.This sensor has additional control circuitry that can prevent inconsistent "bouncy" data depending on the application.Ultrasonic distance measurement can be found in automobile self-parking and anti-collision safety systems, obstacle detection systems for vehicle safety, as well as manufacturing technology. 

## Literature Survey

Objects detecting sensors are one of the most basic type of sensors that engineers use. There are several method to make cheap object sensors. These simple sensors are made using a IR Rx /Tx pair or Normal LED and LDR pair . These sensor may be useful for simple requirement but they have the following drawback
1. Cant say anything about the real distance of objects.
2. Give different result for different coloured objects .
3. Need calibration( like setting up a variable resistor).
To solve these problem initially IR Range Finder modules were used but they had small
range.

Later to solve all these problem ultrasonic range finder module were used. These modules uses ultrasonic sound waves inaudible to human. These modules consist of ultrasonic transmitter that emits ultrasonic waves, the waves after striking the objects gets reflected back and is detected by the ultrasonic receiver. By measuring the time taken in the whole process we can detect the distance of the object from the sensor. Ultrasonic sensor can detect the object in the range of 400cm which makes it the ideal for distance measurement application.

## Working Principle

In this project, we have used an HCSR-04 to determine the distance of an obstacle from the sensor. The basic principle of ultrasonic distance measurement is based on ECHO. When sound waves are transmitted in the environment then waves are returned back to the origin as ECHO after striking on the obstacle. So we only need to calculate the traveling time of both sounds means outgoing time and returning time to origin after striking on the obstacle. As the speed of the sound is known to us, after some calculation we can calculate the distance. 
Ultrasonic sensors are also used as level sensors to detect, monitor, and regulate liquid levels in closed containers (such as vats in chemical factories). Most notably, ultrasonic technology has enabled the medical industry to produce images of internal organs, identify tumors, and ensure the health of babies in the womb.

## Components used

# •	Microcontroller ATMega 328:

The ATmega328 is a single-chip microcontroller created by Atmel in the megaAVR family.  It has a modified Harvard architecture 8-bit RISC processor core. The Atmel 8-bit AVR RISC-based microcontroller combines 32 KB ISP flash memory with read-while-write capabilities, 1 KB EEPROM, 2 KB SRAM, 23 general-purpose I/O lines, 32 general-purpose working registers, 3 flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a byte-oriented 2-wire serial interface, SPI serial port, 6-channel 10-bit A/D converter (8 channels in TQFP and QFN/MLF packages), programmable watchdog timer with internal oscillator, and 5 software-selectable power-saving modes. The device operates between 1.8 and 5.5 volts. The device achieves throughput approaching 1 MIPS/MHz.

![image](https://user-images.githubusercontent.com/71214652/164970383-ef94faad-2760-46e9-bee0-07261d6f85ef.png)

 
# •	Ultrasonic Sensor (HC-SR04):

At its core, the HC-SR04 Ultrasonic distance sensor consists of two ultrasonic transducers. The one acts as a transmitter which converts electrical signal into 40 KHz ultrasonic sound pulses. The receiver listens for the transmitted pulses. If it receives them it produces an output pulse whose width can be used to determine the distance the pulse travelled. As simple as pie!
The sensor is small, easy to use in any robotics project and offers excellent non-contact range detection between 2 cm to 400 cm (that’s about an inch to 13 feet) with an accuracy of 3mm. Since it operates on 5 volts, it can be hooked directly to an Arduino or any other 5V logic microcontrollers.

![image](https://user-images.githubusercontent.com/71214652/164970454-e51396d2-7305-40f2-8cf3-77854f8483ab.png)

# •	LCD display (Hd44780-50):

The HD44780U dot-matrix liquid crystal display controller and driver LSI displays alphanumerics, Japanese kana characters, and symbols. It can be configured to drive a dot-matrix liquid crystal display under the control of a 4- or 8-bit microprocessor. Since all the functions such as display RAM, character generator, and liquid crystal driver, required for driving a dot-matrix liquid crystal display are internally provided on one chip, a minimal system can be interfaced with this controller/driver. A single HD44780U can display up to one 8-character line or two 8-character lines.

# •	I2C to Parallel:

The I2C bus is a very popular and powerful bus used for communication between a master (or multiple masters) and a single or multiple slave devices. The I 2C bus is a standard bidirectional interface that uses a controller, known as the master, to communicate with slave devices. A slave may not transmit data unless it has been addressed by the master. Each device on the I 2C bus has a specific device address to differentiate between other devices that are on the same I 2C bus. Many slave devices will require configuration upon startup to set the behavior of the device. This is typically done when the master accesses the slave's internal register maps, which have unique register addresses. A device can have one or multiple registers where data is stored, written, or read.

# •	BJT :

This is the bipolar junction transistor. The primary function of BJT is to increase the strength of a weak signal, i.e., it acts as an amplifier.

# •	Resistor: Two resistors of 2.2kΩ is used in this project.

A resistor controls the flow of the electrical current within a circuit.

# •	LED:

This light emitting dioide is used as it produces light by passing the electric current through a semiconducting material.

## Applications

1. Speed check in roads

2. Driverless cars to detect obstacles.

3. Radars for robotics.

4. Fuel level in the tank


