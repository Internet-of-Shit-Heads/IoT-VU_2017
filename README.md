# IoT-VU 2017/18 lab project

This repository serves as an overarching repo for our IoT-project for the IoT course at TUW 2017/18.

For more information about the purpose and design decisions behind the project, please refer the [documentation](docu).

The subprojects are:

 - [Dashboard](https://github.com/Internet-of-Shit-Heads/Coordinator_Node/tree/4c7671018e276e860dedb3372891ff0d6c3b086b): A (very simple) HTTP dashboard that display the sensor values. Using paho-mqtt.js to connect to a MQTT broker via websockets, and Google charts to display the values.

 - [RFnode](https://github.com/Internet-of-Shit-Heads/RFnode/tree/cc2af83b3421f3a7ac8289e8c6aff94748f121a1): Arduino project for the low-power RF-Nodes (sensors)

 - [Coordinator Node](https://github.com/Internet-of-Shit-Heads/Coordinator_Node/tree/4c7671018e276e860dedb3372891ff0d6c3b086b): Arduino project for the ESP8266 Coordinator node

 - [Broker Config](https://github.com/Internet-of-Shit-Heads/broker_config/tree/a5848a51a7991a2f83d627a33f464431d6348e63): Configuration files for the MQTT broker (mosquitto)

 - [CA helbers](https://github.com/Internet-of-Shit-Heads/ca-helpers/tree/b3e1904ab6bb89eb84d410408145b0c029f97d87): Helpers to create the required CA certificates

Dependencies for Ardino libraries are references as submodules in the [libraries](libraries) folder.
