Integrated Situation: Smart Water Management System

Project Overview

The WASAC Group is developing a Smart Water Management System that enables users to remotely monitor and manage their water consumption. Through an online platform, users can track their water usage and set a maximum daily consumption limit.

Automated Valve Control

The system is designed to automatically close the water valve when:
	1.	The user’s balance reaches zero.
	2.	The daily preset consumption limit is exceeded.

With edge processing, these decisions can be made locally, even if the system is offline.

Prototype Simulation

Objective:

To develop a basic prototype using an ESP32 microcontroller in VS Code and simulate the system’s functionality.

Prototype Features:
	•	Three houses connected to a single ESP32.
	•	Three buttons to decrease each user’s balance (representing water usage in liters).
	•	Three buttons to increase each user’s balance (representing balance top-up in liters).
	•	Two LED indicators:
	•	Red LED → Balance zero (valve closed).
	•	Green LED → Balance greater than zero (valve open).
	•	A monitoring platform to display real-time water consumption and user balances.

Tasks and Evaluation (5 Days)

Task 1: Simulating the Prototype (Wokwi + Google Cloud) – 5 Marks
	•	Use Wokwi Simulator in VS Code to implement the prototype.
	•	Store and retrieve data using Google Cloud as a database.
	•	Ensure real-time synchronization between ESP32 and the monitoring platform.

Task 2: Deployment on GitHub – 5 Marks
	•	Deploy the simulated project on a GitHub page.
	•	Provide a public link for monitoring three users as illustrated.

Task 3: Enhancing the Simulation (Proteus + Hardware Integration) – 5 Marks
	•	Replace Wokwi with the Proteus Simulator.
	•	New Features:
	1.	Keypad for balance entry.
	2.	Flow sensor to track water usage and automatically debit the balance.
	3.	LCD display to show real-time balance.
	4.	LED indicators:
	•	Red LED → Balance zero (valve closed).
	•	Green LED → Balance greater than zero (valve open).

This structured approach ensures a clear roadmap for development and assessment, helping the research team efficiently prototype, deploy, and enhance the Smart Water Management System.
