# ⚡ **Nexus Scanner** ⚡  
> A sleek interface to scan and interact with Modbus devices over serial connections.

![Modbus Banner](https://via.placeholder.com/1200x300?text=Modbus+RTU+Scanner+%7C+Cross-platform+Modbus+Client)  

---

## 🚀 **Overview**  
The **Nexus Scanner** is a cross-platform tool for **Windows** and **Linux** that allows users to scan, read, and write to Modbus devices connected over **serial ports**.  
With a clean web-based user interface, this tool makes it easy to configure your Modbus settings, view real-time register data, and interact with your devices seamlessly.

---

## 🎯 **Features**  
- **Cross-platform support** (Windows and Linux)  
- **Scan Modbus registers** in real-time (Coils, Discrete Inputs, Holding Registers, Input Registers)  
- **Write to Modbus holding registers**  
- **Auto-detect serial ports**  
- **Sleek UI with background particles for visual appeal**  
- **User-friendly configuration options** (COM port, baud rate, parity, stop bits, and more)  

---

## 🖥️ **User Interface**  

![UI Preview](https://via.placeholder.com/800x400?text=UI+Preview+Placeholder)  

**Core UX Elements:**  
1. **COM Port Selection**: Auto-detects all available serial ports.  
2. **Modbus Configuration Fields**: Easily set baud rate, parity, stop bits, slave ID, and more.  
3. **Scan Controls**: Start/Stop scanning and view register values in real-time.  
4. **Write Controls**: Send values directly to Modbus holding registers.  
5. **Responsive UI**: Works across desktop and mobile browsers.

---

## 📋 **Installation**  

### Prerequisites  
- Serial drivers (e.g., `CH340`, `FTDI`) installed for your device if needed.  


## ⚙️ **Configuration**  
The following settings can be configured via the web interface:  

| **Setting**       | **Description**                                   |
|-------------------|---------------------------------------------------|
| **COM Port**      | Select the serial port (e.g., `/dev/ttyUSB0`, `COM3`) |
| **Baud Rate**     | Communication speed (9600, 19200, etc.)            |
| **Parity**        | None, Odd, or Even                                 |
| **Stop Bits**     | 1 or 2                                             |
| **Slave ID**      | Modbus device identifier (0-247)                   |
| **Function Code** | Select function: Coils, Inputs, Registers, etc.    |

---

## 🖥️ **Supported Commands**  
- **Read Coils** (Function Code 1)  
- **Read Discrete Inputs** (Function Code 2)  
- **Read Holding Registers** (Function Code 3)  
- **Read Input Registers** (Function Code 4)  
- **Write Single Register**
- **Convienient interface for Read/Write bits registers**

---

## 🛠️ **Platform Support**  
- **Windows**: Auto-detects available COM ports.  
- **Linux/macOS**: Lists `/dev/tty*` devices for easy access to serial interfaces. (Soon)

---


## 📜 **License**  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📷 **Screenshots**  
### UI Example  
![Screenshot Example](https://via.placeholder.com/800x400?text=Screenshot+Placeholder)  

---

## 🔗 **Contact**  
- **Author**: Nexus Technologies 
- **Email**: [your-email@example.com](mailto:scanner@nexus-te.com)  

--

## 🎉 **Enjoy Scanning!**  
![Footer Banner](https://via.placeholder.com/1200x200?text=Happy+Scanning+%7C+Modbus+Made+Simple)  

---
