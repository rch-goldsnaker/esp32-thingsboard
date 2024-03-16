## <a name="introduction">💻 Esp 32 to Thingsboard</a>

<img src="https://github.com/rch-goldsnaker/esp32-thingsboard/blob/main//banner.png" alt="Project Banner">

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 💻 [Youtube tutorial](#youtube)
5. 🤸 [Quick Start](#quick-start)
   
## <a name="introduction">🤖 Introduction</a>

We are going to connect an ESP32 to a specific Wi-Fi network and it will send temperature and humidity data, obtained through a DHT22 sensor, to a ThingsBoard server via MQTT, using an access token for authentication. The device will be responsible for keeping the Wi-Fi connection active, continuously collecting sensor data, and sending it to the server. This entire process will be carried out in a constant execution loop. Additionally, for this development, we will be using an ESP32 emulation on the Wokwi platform.


## <a name="tech-stack">⚙️ Tech Stack</a>

💎 Esp32 

💎 Arduino Framework

💎  Thingsboard

💎 MQTT Protocol

💎 ArduinoJson Library

## <a name="features">🔋 Features</a>

👉Wi-Fi Connection: The device connects to a specific Wi-Fi network using the provided credentials.

👉 Temperature and Humidity Sensor: It utilizes a DHT22 sensor to gather temperature and humidity data from the environment.

👉 MQTT Communication: Sends the collected data to the ThingsBoard server via the MQTT protocol, using an access token for authentication.

👉 Connection Management: It ensures to keep the Wi-Fi connection active and automatically reconnects if the connection is lost.

👉 Constant Execution Loop: The device continuously collects sensor data and sends it to the server in a constant execution loop.

👉 Wokwi Emulation: The code is developed and tested using an ESP32 emulation on the Wokwi platform.

## <a name="youtube">🎬 Youtube tutorial</a>

See tutorial video [here](https://www.youtube.com/watch?v=04aKK_7yCqc)

## <a name="Deploy">🚀 Deploy</a>

See online [here](https://wokwi.com/projects/387608925575245825)