# EnviroGuard
UAV-Plastic-Remover
This project aims to develop an Unmanned Underwater Vehicle (UUV) capable of detecting and removing underwater plastics using the YOLO (You Only Look Once) v8 object detection algorithm.

Table of Contents
Introduction
Material-used
System-Components
Work-flow

Introduction
Underwater plastics are a significant environmental issue, as they can harm marine life, contaminate water sources, and accumulate in the food chain. This project addresses this issue by developing a UUV that can autonomously detect and remove plastics from underwater environments.

The UUV utilizes the YOLO (You Only Look Once) object detection algorithm to identify plastics in real time. YOLO is a real-time object detection system that is fast and accurate, making it suitable for use in UUV.

Material-used
Material: We are using aluminum stainless steel as a primary material for making the parts. Aluminum stainless steel is being used because of its, anti-corrosive, strength, durability, and aluminum lightweight properties. Every part and the electrical components have been encapsulated and coated with silicon to make it waterproof.

Battery: The battery used is an aluminum ion battery in which the battery drinks water to generate energy. Here, the aluminum anode combines with water molecules which in turn releases hydroxide and hydrogen gas which are harmless from the emission from any other battery including lithium-ion battery which is being used in general. The electrons transferred in this process are converted into energy. This makes the product more efficient and allows the drone to work environment-friendly.

Thrusters: We have used brushless DC motors (BLDC) for their high and efficient performance and their high thrust-to-weight ratio.

Collector: A flexible nonvolatile and highly durable net is being used in our UUV.

System-Components
1. Hardware setup:
Right now we are using Raspberry Pi 4 and Raspberry Pi Camera Module 2 to demonstrate the workflow.

2. Software setup:
Using the necessary libraries for the Raspberry Pi 4 and configuring them enables us to bridge a connection between the Raspberry Pi 4 and the Raspberry Pi Camera Module 2. By these, we can easily implement the YOLO v8 object detection algorithm.

Work-flow
First, the UUV is dropped in the ocean. The propeller of the UUV is used to navigate under the water. The camera modules ( DTG3 underwater camera) in the head as well as in the palm of the robotic arm are used to detect the plastics which is either floating or submerged in the ocean. The sonar sensors which are also present in the hand of the robotic arm are used to calculate the distances. The data from the camera and the sensors are passed to the processor which manipulates the robotic arm to pick the plastics. Then the plastics are placed on the UUV which is then sucked into the net. Likewise, the plastics under the ocean are cleaned.

Link for model
The link for YOLO model: link(https://colab.research.google.com/drive/1NyjogvBtkPfD9gc0fwTjT8qEMeACpJdI?usp=sharing)
