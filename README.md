# esp32_idf_camera_app
ESP32 camera firmware that support various camera models

# Camera with Web Server

# Preparation

To run this example, you need [ESP-IDF](https://github.com/espressif/esp-idf)

# Quick Start

After you've completed the hardware settings, please follow the steps below:

1. **Connect** the camera to ESP32 module;
2. **Configure** the example through `make menuconfig`  
or the faster `idf.py menuconfig` if you are using [ESP-IDF v3.1 or above](https://github.com/espressif/esp-idf/tree/release/v3.2), that support Cmake;
3. **Build** the application`make all` or the faster `idf.py build`;
4. **Flash** the application`make flash` or `idf.py flash`;
5. **Open Your Browser** and point it to `http://[ip-of-esp32]/`;  
If you use AP mode, first connect to AccessPoint created by ESP32;
6. **To Get Image** press `Get Still` or `Start Stream`;
7. **Use The Options** to enable/disable Face Detection, Face Recognition and more;
