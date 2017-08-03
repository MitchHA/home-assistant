# home-assistant
Running Hassbian on a Raspberry Pi 3 with all physical connections moved off the Pi onto 3 NodeMCU's and 2 Wemos D1 Mini's. Using the Open MQTT RF/IR code (https://github.com/1technophile/OpenMQTTGateway) to provide 433meg RF,IR to my digibox and room temperature/humidity - thanks Florian :)

Have multiple RF 433Mhz sockets controlling lights and bedroom fan. Soon to be moved on Sonoff's once I get new living room lights.

Using the multisensor code from Bruh (https://github.com/bruhautomation/ESP-MQTT-JSON-Multisensor) on the NodeMCU's and Wemos to gather temperatures around the house and provide motion sensing on the 3 house entry points. 

Have Nest Thermostat in the hallway also pulling in the hallway temps. Amazon Dot in the living room provides voice control into HA using emulated hue.


