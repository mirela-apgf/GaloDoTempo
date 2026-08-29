<p align="center">
  🌐 <b>Languages:</b> 
  <b>English 🇺🇸</b> • 
  <a href="./README.pt-BR.md">Português 🇧🇷</a>
</p>

# 🐔 Galo do Tempo

IoT and Cloud Computing project inspired by the traditional weather rooster, combining a DHT11 sensor, ESP32, cloud data storage, and a web interface.

The system collects temperature and humidity data from the environment and sends it to ThingSpeak through Wi-Fi. The website then uses the humidity data to automatically change the rooster's color according to the current condition.

<br>

## 🚀 Features

* Monitor temperature and humidity
* Collect data using the DHT11 sensor
* Send data to the cloud through the ESP32
* Store data using ThingSpeak
* Automatically change the rooster's color based on humidity

<br>

## 🛠 Technologies

* ESP32
* DHT11
* C/C++ (Arduino)
* ThingSpeak
* PHP
* HTML
* CSS
* JavaScript

<br>

## 💡 Usability

The project provides a simple and visual way to understand the humidity level of the environment through the rooster's color:

* 💙 **0% – 39%:** Dry
* 💜 **40% – 69%:** Moderate humidity
* 💗 **70% – 100%:** Very humid

<br>

## 📸 System Interface

<p align="center">
  <img src="readme/imagens/GaloDoTempo.png" width="100%">
  <img src="readme/imagens/GaloDoTempo.png" width="100%">
  <img src="readme/imagens/GaloDoTempo.png" width="100%">
</p>

<br>

## ▶ How to Run

1. Clone the repository
2. Upload the ESP32 code from the `esp32` folder
3. Configure the Wi-Fi and ThingSpeak credentials
4. Set up the PHP website in a local server
5. Access the website through the local server
