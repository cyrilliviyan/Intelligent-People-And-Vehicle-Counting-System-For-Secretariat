# Intelligent-People-And-Vehicle-Counting-System-For-Secretariat
Security is a top priority for states, and a system should be developed to monitor people and vehicles entering and leaving locations. Cameras detect entry and exit, capture faces, count people, and cars, and send captured data to a cloud-based mobile application for continuous monitoring and patrolling.

Prerequisites
  1)IBM Account creation:
          *To complete this project, you must have knowledge of the following Cloud Services:

IBM Watson IoT Platform
   2) Node-RED installation :
         In order to implement the project successfully, we make use of Node-RED Service in our local system. This platform is part of node-js, enabling us in creating enhanced and impressive User Interfaces.

Follow the below step to initialize a node-RED Service:

Install node-js to the local system from the internet.

Once the installation is completed, open the command prompt and feed in the following command: node-red

The node red service will be running in the mentioned url after the command runs successfully.

To stop the Node-RED service, press ctrl+C or simply close the terminal window.

3)install Python
       Install the following Python libraries, that will be useful in successful compilation of the device code:


Numpy (pip install numpy)

Pandas (pip install pandas)

OpenCv (pip install opencv-python)

Pyttsx3 (pip install pyttsx3)

pip install ibmiotf
Project Flow

The device code with the help of opencv will analyze the video and capture the number of people going in and coming out of the designated venue.
This captured information is published in the cloud (ibm iot device).
Sensor data is visualized in the Web Application.
To accomplish this, we have to complete all the activities and tasks listed below
Create and configure IBM Cloud Services
Create IBM Watson IoT Platform and Device
Create Node-RED service
Develop the Python Script
Develop a web Application using Node-RED Service.
Develop the Web application using Node-RED
Testing the Web UI by giving the required inputs
DEVELOP DEVICE CODE TO PUBLISH AND SUBSCRIBE TO IBM IoT PLATFORM

Develop device code



Develop the device code to send the status of the driver to the IBM cloud. The status of the driver changes as different actions are captured by the camera through OpenCV.

Refer to the below device code to develop the code for this project.



Publish data to the IBM cloud



Python code is used to send random sensor data to the cloud and also to receive commands from the cloud.

When the commands are received just print the statements which represent the control of the devices.

From the above reference code, you will be able to define methods to publish the data onto the IBM cloud, depending upon the project. In this project, we send in the flag values(0 or 1), which are later used in conditional loops to display the message in Web Application.


Refer to the below document for an in-depth process on creating and utilizing the IBM cloud platform and devices.

Develop A Web Application Using Node-RED Service.
