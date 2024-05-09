

# Project - Fall Detection using Mobile Sensor

## In this project, we are detecting falls based on accelerometer metrics. Upon detecting a fall, we will send notifications to the mobile app and activate the buzzer.

## Basic Workflow
1. Use Websocket connection using app Sensor server to accept acceleration values
2. Classify the events based on acceleration values into 5 state.
3. At State 4, there is confirmity that fall is detected.
4. After it, we use Pushbullet API to connect to mobile phone for notification