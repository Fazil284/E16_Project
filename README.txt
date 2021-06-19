PROJECT TITLE: Robotic automated External Defibrillator ambulance for emergency medical service in smart cities. 




ABSTRACT:

India is one of the most populous countries of the world. Due to over population, ignorance of health have been remained the major problems in India. For every one minute a death sw oops in because of heart attack.Ambulance service plays a vital role in saving lives. Its primary purpose is to give first aid to the sick or injured people in the emergency scene. To save a life is auspicious as well as precious.The idea here is to provide an intelligent smart health system using some sensors and microcontrollers; it will sense the body condition and send the data to the collaborated hospital’s database.

This proposed idea gives us the development of a wireless based system for pulse rate, blood pressure and temperature monitoring to be used in ambulance. By this, the real time information can be passed to nearby hospitals to alert them about the critical conditions over IOT.This hardware device is fixed inside the ambulance to sense the patient’s health, collect the data in a wireless device called node MCU and immediately pass the database to the hospital’s server by the concept of IOT. This may intimate the hospital officials and may respond to the necessary actions to be taken to the person in emergency.



INTRODUCTION :

	Traffic signals in India has a fixed time period to switch the signals. No changes for emergency vehicles.
	This makes the patient in ambulance to sever stage. To deal with this problem we designed this system.
	So we propose an IOT-based system for patients with the risk of heart attack and uneven body temperature, high pulse rate.
	If the condition is critical an alert notification will be sent to the hospital monitoring database.
	This system consists of various sensors which collects the patient's information and transmit those information to the server via IOT board.



STEPS
****************************************************************************************************************
1.DATA COLLECTION FROM PATIENT’S BY USING SENSOR

 Sensor is a devices to measure temperature, pulse, heart beat readings through electrical signals.
  Temperature is   the   most common  physical	measurement type in industrial applications.
 Pulse sensors use the photoelectric method.
 The heart rate sensor measures your heart rate in Beats per Minute using an optical LED light source and an LED light sensor.
 The sensor will get the information of patient’s temperature, pulse, heartbeat and transmit it into microcontroller.


2.TRANSMIT DATA FROM ARDUNIO TO IOT BOARD BY USE OF UART PROTOCOL

	Microcontrollers can take inputs from the device they controlling and retain control by sending the device signals to different parts of the device.
	Microcontroller will transmit data from arduino to IOT board by using UART protocol.
	It provides  transmit data  and a receive data and then send it to the server.
	And it will be stored in server and display that information to the doctor.


3.TRANSMIT DATA FROM IOT BOARD TO SERVER BY USE OF MQQT PROTOCOL

	IOT board will transmit the data to server by use of MQQT protocol.
	IoT prototyping kits and development boards combine microcontrollers and processors.
	MQ Telemetry Transport is an extremely simple and lightweight messaging protocol (subscribe and publish) designed for limited devices and networks with high latency, low bandwidth or unreliable networks. By using the data received from controller the doctor can suggest the treatment to the patient.
	As it reduces the human effort then it definitely saves out time.

*************************************************************************************************************


Project Link: https://github.com/Fazil284/E16_Project
