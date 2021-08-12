# Arduino-Opla-Kit-Project

## Description

Simple desk assistant built with Arduino-Opla-Kit.
The assistant ha the following features:

    - shows the weather information 
    - emits sound if someone is near the assistant
        - check presence sensor status
        - enable/disable the presence sensor
        - send a notification to cellphone via Blink app
    - show a list of messages sent to the assistant


For italian only, please check my [video](https://youtu.be/ERMxU6fnjtQ) for more information.


## Requirements

    - an account on [Arduino IoT Cloud](https://github.com/Cereal84/Arduino-Opla-Kit-Project.git)
    - an Arduino-Opla-Kit

## How to build the project


Create a new Project into Arduino IoT Cloud, on "Setup" page declare the following variables:
    - humidity    , float - read only - periodically (1 sec)
    - light       , int   - read only - periodically (1 sec)
    - pressure    , float - read only - periodically (1 sec)
    - temperature , float - read only - periodically (1 sec).


After this connect your device, I've used an Arduino MKR WiFi 1010, and add SSID and the password
of your home network.

Download Blynk application on your smartphone and create a new app with:

    - notification
    - text input (Pin V0)

Take a note about your auth code, this one is needed on next step.
Copy the file "Code" into "Sketch" section and change the values for auth, SSID and password.
Open the full editor and add the other file (sun.c, cloud.c, thundertorm.c, rain.c)
After that upload your code and open the serial monitor

Enjoy! :)

## License

Distributed under the MIT License. See LICENSE for more information.

