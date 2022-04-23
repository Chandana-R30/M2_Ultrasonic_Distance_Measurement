#### Ultrasonic Distance Measurement using ATmega328

## Introduction

Distance measurement using HC-SR04 and ATMEGA328p. In this project I have measured distance in centimetres, with the help of HC-SR04 Ultrasounic sensor, ATMEGA328 microcontroller, LCD Display via I2C bus .

## Research

In this project, the Ultrasounic sensor uses a technique called “ECHO” which is something you get when sound reflects back after striking with a surface. We know that sound vibrations can not penetrate through solids. So what happens is, when a source of sound generates vibrations they travel through air at a speed of 220 meters per second. These vibrations when they meet our ear we describe them as sound. As said earlier these vibrations can not go through solid, so when they strike with a surface like wall, they are reflected back at the same speed to the source, which is called echo. Ultrasonic sensor “HC-SR04” provides an output signal proportional to distance based on the echo. The sensor here generates a sound vibration in ultrasonic range upon giving a trigger, after that it waits for the sound vibration to return. Now based on the parameters, sound speed (220m/s) and time taken for the echo to reach the source, it provides output pulse proportional to distance.

## Features

•	Microcontroller : ATmega328
•	Operating Voltage : 5V
•	Program Memory Type : Flash
•	Flash Memory : 32Kbytes
•	SRAM : 2 KB (ATmega328)
•	EEPROM : 1 KB (ATmega328)

## SWOT Analysis

# Strengths

•	Distance of the objects can be calculated without error
•	Can locate the object
•	Low cost and efficient solution

# Weakness

•	The developed system is applicable only for solid objects.

# Opportunities

•	We can use humidity sensors in future to measure distance in different environment
•	This system can be used in driverless car to detect obstacle

# Threats

Any acoustic noise at the frequency to which the ultrasonic sensor is receptive, may interfere with that sensor's output
# 4W's and 1H
# Who :
Its easy to use this device by anyone.

# What :
Distance measurement of objects with the help of HC-SR04 Ultrasounic sensor, ATMEGA328 microcontroller, LCD Display via I2C bus.

# When :
This is done as a Module-2 Embedded project.

# Where :
This is done on Visual Studio Code and SimulIDE.

# How :
Implemented by using the Embedded system concepts and C program.

