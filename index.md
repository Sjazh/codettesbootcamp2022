# Codettesbootcamp2022

## 10 Interface & Application Programming

**Objectives**

*Wk 1*

[x] Setup Dev Environment for ESP32 S2

[x] Setup NodeJS Dev Environment on your PC

[] Explain the HackOmation quadrant in relation to your final project.

[] Build UI mockups for your Final Project and HTML Layout

*Wk 2*

[] Build HTML5 Chat app
* Draw mockup / layout
* frame and add id’s to <div>’s
* Style the page and 
* wire up the JS code and understand
  
*Wk 3*
  
[] Build Chat app back-end NodeJS
* Build NodeJS server side to: 
* host your ChatApp (Express static HTML)
* Build / test API endpoints (for: users & messages)
  
*Wk 4*
  
[] Setup MongoDB datastore & connect via NodeJS
* Setup MongoDB datastore + mongoose ODM (Object-Document-Manager)
* Store and recall message data using an API (ex. request top 100 msg)
* Wire up MongoDB to API endpoints
* Update app-flow to use back-end for Users and “old” messages
  
Wk 5
  
[] Create data-bound widgets to display sensor data
 * On ESP32 add MQTT client + ArduinoJSON
 * Send Sensor data to MQTT server (as a JSON object)
 * Create a DataCard, a Gauge and a time Chart widget on Dashboard (use chat app)
 * Strategy on DataBinding and Widget updating (Last updated)
 * User Login/Pw (state persistence)

[] Add Screenshots and description of the process of creation. 
  
[] Describe the design & programming steps
  
[] Screenshots or video of your Prototype/app working
  
[] Describe any errors or problems with the process and how you fixed them. 
  
[] Include all the files you created for download. 


  
  
### 10.1 Setup Dev environment ESP32 S2
#### 10.1.1 What is ESP32?

ESP32, like Arduino, is a development board. That means it has all the features you need to create your projects. ESP32 is a low-powered, low-cost microcontroller (MCU) board, with both Wi-Fi and Bluetooth built in, and is based on a dual-core processor mechanism.

#### 10.1.2 Install ESP32 board in Arduino IDE

There’s an add-on for the Arduino IDE that allows you to program the ESP32 using the Arduino IDE and its programming language.

I used the following instructions to install the ESP32 board in Arduino IDE:

1. In your Arduino IDE, go to File> Preferences and enter the following into the “Additional Board Manager URLs” field:
   ![](images1/image1.png)
