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
   https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json
   ![](images1/image1.png)
  
  
2. Open the Boards Manager. Go to Tools > Board > Boards Manager…
   ![](images1/image2.png)
  
  
3. Search for ESP32 and press install button for the “ESP32 by Espressif Systems“:
  ![](images1/image3.png)
  
  
4. Checking if ESP32 is available 
  ![](images1/image4.png)

  
### 10.7 3D Printing
#### 10.7.1 What is 3D printing

Turns digital 3D models into solid objects by building  them up in layers. The 3D printing process turns a whole object into thousands of tiny little slices, then makes  it from the bottom up, slice by slice. Those tiny layers stick together to form a solid object.

#### 10.7.2 3D Printers & Filaments
  There arre two type of printers:
  1. ** Anycubic Predator (DeltaBot) ** :is a consumer 3D printer that uses DeltaBot technology (three robotic arms attached to a base). The Deltabot uses a print head     attached to 3 sets of robotic arms to deposit the material.
  2. ** Anycubic 4 Max Pro **: Enclosed Printing space with larger build volume enhance the printing quality, out of box, no need assemble, optional auto power off feature is safer for children. Patented printing platform with excellent adhesion whilst printing and pop off once it cools down. The sensor triggers the machine to pause prints and set off an alarm when filament run out.

  We will be 3D printing with the Anycubic Predator (Deltabot)
  
  There are two filaments:
  1. PLA (Polylactic acid)
  2. ABS (Acrylonitrile Butadiene styrene)
  
  PLA and ABS are both thermoplastics. PLA is stronger and stiffer than ABS, but poor heat-resistance properties means PLA is mostly a hobbyist material. ABS is weaker less rigid, but also tougher and lighter, making it a better plastic for prototyping applications.

  We will be working with the PLA Filament.
  And these are the PLA parameters we have to keep in mind while creating something in Cura
  ![](images1/image3D.2.jpg)
  
#### 10.7.3 Installing Cura
  Cura is an open source slicing application for 3D printers.
  For the bootcamp we will be using Cura for 3D printing.
  
  I used this link to install Cura version 5.0.0: https://github.com/Ultimaker/Cura/releases/tag/5.0.0
  ![](images1/image3D.1.png)
  
  After installing Cura from the .exe file i choosed the "sing up for free" option.
  
  Cura Installed:
  ![](images1/image3D.3.jpg)
  
#### 10.7.4 Cura settingss
The first we need to do when after opening Cura after installing is selecting the printer we will be working with. So as I said we will be using the Anycubic(Deltabot) printer so i have to to select the anycubic printer. 
That can be done by following this:
  ** SETTINGS → PRINTER → Manage Printer **
  ![](images1/image3D.4.jpg)
  
  After clicking manage printers we have to click on "Add New" and search for the anycubic predator printer in the "Add a non-networked" bar.
  ![](images1/image3D.5.jpg)
