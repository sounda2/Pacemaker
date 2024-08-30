# Pacemaker

## Project Description
In a team of five, we tackled the Boston Scientific Pacemaker System Challenge, which involved developing an effective pacemaker system. Our task encompassed analyzing the provided documentation, defining the project scope, outlining requirements, and implementing both the pacemaker’s embedded software and a Device Control Module (DCM). The pacemaker was simulated on a hardware platform using a K64F board to represent the pacemaker and an STM32 Nucleo board to simulate the heart, with driver circuits for both. The embedded software was developed using MATLAB Simulink. The DCM, which included a GUI, allowed users to program the pacemaker and manage incoming data. My primary contribution was creating the DCM using Tkinter in Python, and I also assisted with the Simulink programming.

## 🔨 Key Skills Used
* Python, Tkinter
* Simulink
* STM32

## 📝 Project Report

For more details on the development of this project, check out the project report [here](https://docs.google.com/document/d/1jzq7RfOgnktOJMuyjjTxeRuv2VOisj7cmwxx3PNMcqw/edit?usp=sharing)

## 📸 Images of the Design

### State Flow Diagram of the DCM

This is the stateflow diagram of the DCM. It describes the overall system functionality of the GUI.

![stateflow_digram](https://github.com/user-attachments/assets/18d26ff2-9eda-4cf2-86c7-63d4ca54d950)

### Welcome State

This is the welcome state of the DCM. Here the user can either login with an existing account or register a new account. 

![welcome_state](https://github.com/user-attachments/assets/558d5de9-d063-432d-a5bd-7d439f28ccfc)

### Registration

When you go to register as a new user, the username is checked against a database of existing users and the password is checked for security. If both pass, then the account credentials are registered and you may log in with your credentials.

![image](https://github.com/user-attachments/assets/10d89a5f-0a28-4169-bfd6-7c568db9d5ea)

### Dashboard State

When the user is presented with the dashboard state, the most recently used Pacemaker mode is preselected along with the parameter values that were last saved. If it is a new user, default or nominal values are placed for each parameter. Not to mention, there are indicators for if the DCM is communicating with a device or a new device.

![image](https://github.com/user-attachments/assets/7b30d749-e7ab-46a5-a9ad-501c68c8e618)
![image](https://github.com/user-attachments/assets/91940759-7aad-4139-9a9d-2813ca340f3f)


