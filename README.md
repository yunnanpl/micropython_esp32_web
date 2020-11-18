# micropython_esp32_web
Working and stable esp32 micropython web server.
Unfortunately it required a lot of testing, to go from the basic examples to a stable working web server.
Now it easily survives days, multiple request from multiple clients, etc.

Testing included: timeout errors, iphone killing sockets, sending errors and more.

Idea is:
= sensors (different MQ sensors and temperature sensors)
  mainly natural gas and carbon monooxide for gas heater safety
= webpage and mqtt connection
= bluetooth eq3 thermostats control
= bluetooth scanner for presence testing

Created and tested on
= esp32-idf4-20201114-unstable-v1.13-173-g61d1e4b01.bin
= esp32-wroom-32 (from AZ-Delivery)

Helpful projects
https://github.com/leech001/MQ9
https://github.com/kartun83/micropython-MQ

Page layout and basics from
https://randomnerdtutorials.com/esp32-esp8266-micropython-web-server/
