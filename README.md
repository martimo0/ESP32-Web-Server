# ESP32-Web-Server

Learning the basics of the ESP32 through making a simple web server to control LEDs following an online tutorial by Random Nerd Tutorials (https://randomnerdtutorials.com).

After purchasing a starter kit for the ESP32 I found this online tutorial to create a basic web server that will control LEDS utilising Wi-Fi and a web server so I decided to document this.

I began with setting up the Arduino IDE which I will be using to upload code to the ESP32 via a USB-C cable. Afterwards I ran the classic Blink test which already had a preorganised sketch within the Arduino IDE itself. I only had to change it so that the 2nd blue LED would light up on the ESP32 (given the red LED already lights up as it's plugged in). The Blink INO file is also added.

Afterwards I followed the guide to set up the circuit specifically using this image:


<img width="624" height="500" alt="WebCircuit" src="https://github.com/user-attachments/assets/dea86d62-b2bd-469c-9d85-cab0aeb9a482" />

(taken from the tutotrial PDF for ESP32 web server tutortial from https://randomnerdtutorials.com)

The web server was configured using the code found here: https://github.com/RuiSantosdotme/ESP32-Course/blob/master/code/WiFi_Web_Server_Outputs/WiFi_Web_Server_Outputs.ino

I only changed the Wi-Fi's SSD and password accordingly to fit my personal Wi-Fi.

Following these steps I successfully created a functioning prototype that can be seen in action.

<img width="4064" height="5358" alt="WebCircuitPhoto" src="https://github.com/user-attachments/assets/71f1fc73-6c47-4dd8-adf9-cb7d27b2fadc" />


Only one of the LEDS is turned "On" controlled from the laptop and can be faintly seen to light up.

Overall, this project is a great beginning step into the world of microcontrollers. I will be looking at following more tutorials or heading straight into my own personal projects. 

Have a nice day!
