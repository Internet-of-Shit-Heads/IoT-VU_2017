# IoT-VU 2017/18 lab project

This repository serves as an overarching repo for our IoT-project for the IoT course at TUW 2017/18.

For more information about the purpose and design decisions behind the project, please refer the [documentation](docu).

The subprojects are:

 - [Dashboard](https://github.com/Internet-of-Shit-Heads/Dashboard): A (very simple) HTTP dashboard that display the sensor values. Using paho-mqtt.js to connect to a MQTT broker via websockets, and Google charts to display the values.

 - [RFnode](https://github.com/Internet-of-Shit-Heads/RFnode): Arduino project for the low-power RF-Nodes (sensors)

 - [Coordinator Node](https://github.com/Internet-of-Shit-Heads/Coordinator_Node): Arduino project for the ESP8266 Coordinator node

 - [Broker Config](https://github.com/Internet-of-Shit-Heads/broker_config): Configuration files for the MQTT broker (mosquitto)

 - [CA helbers](https://github.com/Internet-of-Shit-Heads/ca-helpers): Helpers to create the required CA certificates

Dependencies for Ardino libraries are references as submodules in the [libraries](libraries) folder.
