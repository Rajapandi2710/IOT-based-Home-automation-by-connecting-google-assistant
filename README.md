# IOT-based-Home-automation-by-connecting-google-assistant
In this home automation project, we used Google Assistant, Blynk, IFTTT, and a NodeMCU Wi-Fi module to create a voice-controlled system for a single home appliance. The NodeMCU module is connected to a relay, which controls the appliance.

Here's a step-by-step description of the project:
**Materials Needed:**
NodeMCU Wi-Fi module (ESP8266-based)
Breadboard and jumper wires
Relay module (to control the home appliance)
Smartphone with Google Assistant, Blynk app, and IFTTT app installed
A compatible home appliance (e.g., a lamp)
**Project Description:**
**Hardware Setup: **
Connect the NodeMCU module to the breadboard and provide power (3.3V) and ground connections. Connect the relay module to the NodeMCU module, and the home appliance to the relay module. Ensure the connections are made correctly and safely.
**NodeMCU Code: *
Write code for the NodeMCU using the Arduino IDE. The code should connect to your Wi-Fi network, configure the relay, and handle commands from Blynk and IFTTT.
**Blynk App Setup:**
Set up a new Blynk project, add the NodeMCU device, and create a virtual pin to control the relay.
**IFTTT Applet Creation**:
Create a new applet in IFTTT that triggers the Blynk virtual pin when you use a specific Google Assistant voice command.
**Google Assistant Setup**: 
In the Google Home app, set up Google Assistant to use the IFTTT applet. You may need to link your IFTTT account to your Google account.
**Testing: **
After setting up the hardware, installing the necessary apps, and writing the code, test the system by giving voice commands to Google Assistant. The relay should turn the home appliance on or off based on your commands.
This project demonstrates how you can use Google Assistant, Blynk, and IFTTT to create a voice-controlled home automation system using the NodeMCU Wi-Fi module and a relay. This allows you to control your home appliances with simple voice commands.
