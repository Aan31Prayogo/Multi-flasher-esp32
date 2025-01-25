# 🚀 ESP32 Multi-Flasher Application

A **powerful and efficient tool** to flash programs onto multiple ESP32 devices simultaneously! Designed for developers and enthusiasts, this application simplifies the process of flashing multiple devices, making it faster and more reliable.

> **Built and tested on Windows 10 OS**  
> This project is continuously evolving to meet future development needs.

---

## ✨ For executable app you can click [source](https://drive.google.com/drive/folders/1XEZPVYBE-sqZsMinR7RpTbmcbSPijeEN?usp=sharing)

## 🎯 Features
- ✅ **Simultaneous flashing** of multiple ESP32 devices.
- ✅ Supports `.bin` files exported from Arduino IDE.  
- ✅ Easy-to-use interface and modular design.  
- ✅ Error handling and real-time feedback for each flashing process.  

---

## 📂 Example `.bin` Files

You can generate `.bin` files in Arduino IDE. Follow this [guide](https://randomnerdtutorials.com/bin-binary-files-sketch-arduino-ide/) to export `.bin` files for your ESP32 projects.  
An example `.bin` file folder should contain:
- **`bootloader.bin`**
- **`partitions.bin`**
- **`firmware.bin`**

Here's what the folder might look like:
/bin_files/ │ ├── bootloader.bin ├── partitions.bin └── firmware.bin

## 📊 Example Output
- INFO: Successfully flashed on COM1
- INFO: Successfully flashed on COM2
- ERROR: Invalid path file on COM3
