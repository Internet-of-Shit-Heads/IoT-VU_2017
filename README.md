# IoT-VU 2017/18 lab project

This repository serves as an overarching repo for our IoT-project for the IoT course at TUW 2017/18.

For more information about the purpose and design decisions behind the project, please refer the [documentation](docu).

The subprojects are:

 - [Dashboard](Dashboard): A (very simple) HTTP dashboard that display the sensor values. Using paho-mqtt.js to connect to a MQTT broker via websockets, and Google charts to display the values.

 - [RFnode](RFnode): Arduino project for the low-power RF-Nodes (sensors)

 - [Coordinator Node](Coordinator_Node): Arduino project for the ESP8266 Coordinator node

 - [Broker Config](broker_config): Configuration files for the MQTT broker (mosquitto)

Dependencies for Ardino libraries are references as submodules in the [libraries](libraries) folder.
