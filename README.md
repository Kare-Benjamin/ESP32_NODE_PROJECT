# ESP32_NODE_PROJECT
The master-node project is part of a hobby project that turned into part of the course material at NTNU.
It contains one master and one sensor node implemented on an ESP32 using Circus Of Things as a backend/frontend solution.
The code is targeted towards usage with Arduino IDE and utilizes open source libraries that should all be publicly available.

The project aims to exploit the two core operations of the ESP32 to demonstrate how agile the microcontrollers are. The master may run communications on one core, namely ESP-NOW and Wi-Fi, and use the other core to control the displays and many more sensors. ESP-NOW is used through interrupts which makes the system even more agile. Because of only having one antenna, the ESP32 can only use either Wi-Fi or ESP-NOW once at a time. 

<h1> Hardware </h1>
<ol>
  <li>ESP32 Microcontroller</li>
  <li>OLED SSD1306</li>
  <li>7-segment display (any generic breakout board)</li>
  <li>BME280</li>
  <li>Standard components (LEDS, Resistors)</li>
  <li>Breadboards and wires</li>
</ol>

<h1> Software </h1>
<ol>
  <li>Account on Circus Of Things</li>
  <li>Arduino IDE</li>
  <li>Libraries (as included in the code)</li>
</ol>
