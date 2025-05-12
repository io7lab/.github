# io7 IOT Platform Introduction
---
The IBM Watson IOT Foundation had been my choice of platform to teach the students the Internet of Things at a University with. It was a quite comprehensive and concise for the IOT subject, so it was much appreciated and enjoyed. 

But it's unfortunetly decided that the IBM Watson IOT Foundation got sunset and no more available, so this io7 IOT Platform of a minimum set of IOT platform has been developed.

The main purpose of developing this platform and the submodules is to take the essential concepts from the IBM Watson IOT and to come up with a minimum but all required features with which the students can learn and practice the Internet of Things.

--- 

![259081527-279e44bc-265c-4149-9b36-d10a3ace046f](https://github.com/io7lab/io7-platform-cloud/assets/13171662/e07132d7-ed5b-4601-953b-e88481724b1c)

### This is the message subscription and publication authorization for the devices and the application id.
![Screenshot 2024-04-12 at 10 40 32 AM](https://github.com/io7lab/.github/assets/13171662/8da6b017-b74c-4e04-ada8-c2645bd57f56)

### This is the architecture diagram.

<img width="1350" alt="Screenshot 2024-03-22 at 2 42 40 PM" src="https://github.com/io7lab/io7-platform-cloud/assets/13171662/a279d954-6b43-421d-8588-b54fccc5e3a6">

*Archtecture and Usage will be further documented here soon.*

# Github repositories for the io7 Platform


1. https://github.com/io7lab/io7-platform-cloud : the current Repository. This has the installation shell scripts which will install the following components onto the io7 IOT Platform server on an EC2 instance or a dedicated server.
2. https://github.com/io7lab/IO7F8266 : ESP8266 Arduino Library which helps develop the Arduino io7 device easily.
3. https://github.com/io7lab/IO7F32 : ESP32 Arduino Library which helps develop the Arduino io7 device easily.
4. https://github.com/io7lab/IO7FuPython : ESP32 Micropython Library which helps develop the Micropython io7 device easily.
5. https://github.com/io7lab/io7-platform-edge : this repository is for the Edge Server with a Raspberry Pi. This implements an io7 gateway that sits between the local mosquitto broker on the RPi and the io7 Cloud broker and represents the local io7 edge devices by requesting automatic registration and relaying the mqtt events and commands. This prvodes the Edge Server level NodeRED so the Edge level intelligence can be implemented there.
6. https://github.com/io7lab/io7dummy-device : io7 dummy IOT Device. This emulates the io7 IOT Device and can be used to do a quick check after the io7 IOT Platform setup.
