# CP5-EdgeComputing
>Status: Finished✅

The circuit below is intended to capture information through luminosity sensors
and distance convert into gamified information in dashboards and the platform Tago.Io with communication
established via Node red & broker MQTT.

The reading happens via sensors, arduino performs the Node-red reading, the Node red breaks down the analog information
captured, and sends each information to its respective topic (Tago Io & broker MQTT).

### The Hard(part)ware
<img width="600" alt="info" src="https://github.com/vitordmoura/CP5-EdgeComputing/assets/143143995/d8fcdd0a-4148-4c9f-8e9b-2787b4628fac">

### Information captured via brooker MQTT
<img width="600" alt="info" src="https://github.com/vitordmoura/CP5-EdgeComputing/assets/143143995/001523f7-7a6f-4530-bc97-2c4a917a3ab4">

### Flow to hiveMQ
<img width="600" alt="info" src="https://github.com/vitordmoura/CP5-EdgeComputing/assets/143143995/2edc9d75-060c-41bd-8133-8681e851ed83">

### Flow to Tago.Io
<img width="600" alt="info" src="https://github.com/vitordmoura/CP5-EdgeComputing/assets/143143995/91a3ff40-a1d5-4139-a8af-52c82a03a944">

### Tago.Io Dashboard
<img width="600" alt="info" src="https://github.com/vitordmoura/CP5-EdgeComputing/assets/143143995/d0f16930-b346-418d-abe1-144de81fc307">

### Dependencies 

#### Arduino: ArduinoJson
#### Node-red: node-red-node-serialport

## How to run the application:
1) Open ArduinoIDE, paste the code and upload to Arduino
2) Install Arduino dependencies
4) Download and run <a href="https://nodered.org/docs/getting-started/local">node-red</a>
5) Install node-red dependencies
6) import the flow and deploy on node-red
7) Subscribe to the HiveMQ topic.
   
## Group Members
#### Victor Augusto   RM 553518
#### Vitor Moura      RM 553806
