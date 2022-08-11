# ESPresense Sensors
A custom-made PCB designed for an ESP32 running [ESPresense](https://espresense.com) with weather, light and motion sensors

## Sponsor
![image](https://user-images.githubusercontent.com/13995143/184159660-3a476f93-58ee-4487-b305-6b044c7b1c4e.png)

This project has been sponsored by [PCBWay](https://www.pcbway.com/)!

You can order this project from PCBWay at a $5 discount by using my [referal link](https://www.pcbway.com/setinvite.aspx?inviteid=590728)

## Pinout
- Weather Sensor: SCL - GPIO21, SDA - GPIO22
- PIR Sensor: OUT - GPIO16
- Light Sensor: SCL - GPIO23, SDA - GPIO25

## Tested components
- WeMos D1 Mini ESP32
- 5V BME280 sensor
- 3.3V TSL2561 sensor
- 3.3V AM312 PIR sensor
- 3-pin KF301 connector
- HLK-PM01 Power Supply (5V 3W)

## Board preview
![Assembled](./PCB/Photos/05%20-%20Assembled.jpeg)
More pictures can be found [here](./PCB/Photos)

## Use cases
- In-wall sensors panel with Bluetooth tracking ([example](https://user-images.githubusercontent.com/13995143/182904870-07395cbf-d0ec-4150-bce3-0d9bd180927a.jpeg))
- An all in one sensors box with Bluetooth tracking that runs directly off a power socket ([example](https://user-images.githubusercontent.com/13995143/182908361-53876687-a3c8-4eaa-b51e-a6eea644f2ed.png))

## Safety
For your own safety, do not mess with mains voltage unless you're an electrician!

