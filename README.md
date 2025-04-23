# ESP32 WiFi Penetration Tool

This repository contains a binary file for a WiFi penetration testing tool designed for the ESP32 microcontroller. This tool is intended for educational purposes only and should be used responsibly. 

## Important Notice

**The information provided here is for educational purposes only. Unauthorized access to computer systems, networks, or data is illegal and unethical. The use of this information for illegal activities is strictly prohibited. Always obtain explicit permission from the system owner before conducting any security assessments or testing. The creator of this content assumes no responsibility for any misuse of the information or any consequences that may arise from its use.**

## Overview

The binary file included in this repository is designed to be uploaded to an ESP32 board. Once uploaded, the tool will allow you to scan for WiFi networks and perform penetration testing on the networks within range.

## Getting Started

### 1. Prerequisites

Before you begin, ensure you have the following:

- An ESP32 board
- A computer with the ESP32 Flash Download Tool or esptool installed
- A browser for accessing the web tool interface
- Basic understanding of using the ESP32 Flash Download Tool or esptool

### 2. Uploading the Binary File

You have several options for uploading the binary file to your ESP32:

#### Using the ESP32 Flash Download Tool

1. **Download the binary file**: [Download the bin file](https://raw.githubusercontent.com/Mausam678/wifi-jammer-tool-for-esp32/main/esp32-wifi-penetration-tool.bin) from this repository.
2. **Open the ESP32 Flash Download Tool**.
3. **Connect your ESP32 board** to your computer.
4. **Select the binary file** you downloaded.
5. **Set the address** to `0x10000`.
6. **Click the 'Start' button** to upload the binary file to your ESP32.

#### Using esptool

1. **Download the binary file**: [Download the bin file](https://raw.githubusercontent.com/Mausam678/wifi-jammer-tool-for-esp32/main/esp32-wifi-penetration-tool.bin) from this repository.
2. **Open a terminal or command prompt**.
3. **Run the following command**:

   ```bash
   esptool.py --chip esp32 --port [YOUR_PORT] write_flash -z 0x10000 yourfile.bin

#### Using the Web Tool
1. **Go to the web tool**: https://esp.huhn.me
2. **Connect your ESP32 board to your computer.**
3. **Select the binary file you downloaded.**
**Set the starting address to 0x10000.**
**Click 'Upload' to begin the upload process.**
4. **Configuring the Tool**
**After uploading, connect your ESP32 board to a WiFi network using the credentials provided in the text file.**
**Open any web browser and enter the IP address provided in the text file.**
**You will be able to see a list of WiFi networks available in your vicinity.**

## Usage
**Once connected to the ESP32, you can perform penetration testing on available networks as described in the text file.
Follow the instructions provided in the text file to understand how to interact with the tool and perform various attacks**.

## Disclaimer

The use of this tool is intended for educational purposes and to promote understanding of network security. Always use this tool ethically and with proper authorization. Misuse of this tool can lead to legal consequences.


For any questions or issues, please open an issue in this repository or contact the maintainer.

## **Happy Hacking!**
