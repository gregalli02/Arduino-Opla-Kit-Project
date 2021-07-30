# Arduino-Opla-Kit-Project
This is the code of my last Youtube video. Please check it for more information https://youtu.be/ERMxU6fnjtQ

You must run this code on the Arduino IoT Cloud
https://store.arduino.cc/digital/create?utm_source=influencer&utm_medium=cpc&utm_campaign=summer_sales_2021&utm_content=gregalli02



First of all create a new project and add this variable:

humidity    - float - read only - periodically (1 sec)

light       - int   - read only - periodically (1 sec)

pressure    - float - read only - periodically (1 sec)

temperature - float - read only - periodically (1 sec)



After this connect your device, I've used an Arduino MKR WiFi 1010



And then connect it to your network



Download Blynk application on your smartphone and create a new app with:

Notification

Text input (Pin V0)

Remember the auth code



Copy the file "code" on the sketch section and change the personal value (Auth, SSID, Password)



Open the full editor and add the other file (sun.c, cloud.c, thundertorm.c, rain.c)



After that upload your code and open the serial monitor



Enjoy! :)
