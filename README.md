# 📱 Phone Project

A custom embedded hardware project built around an STM32 microcontroller and Quectel EC25 modem.  
The goal is to design, assemble, and program a complete phone system from the ground up — starting with hardware validation and moving toward a full integrated board.

---

## 🚀 Project Overview

**Step 1 — Hardware Verification (current step)** 
- Bring-up of the main board and peripheral circuits  
- Validate power rails, charging system, and USB interface  
- Test modem communication (EC25) and antenna performance  
- Ensure STM32 programming and serial communication are functional  

**Step 2 — Full System Integration**
- Run the STM32 firmware with modem control and battery management  
- Implement power sequencing and graceful shutdown logic  
- Test full end-to-end operation (voice/data + MCU control)  
- Optimize PCB layout and firmware reliability for production

---

## 🧠 Skills Demonstrated
- **PCB Design:** High-speed routing, impedance control, power delivery, and signal integrity  
- **Embedded Programming:** STM32 firmware (C), peripheral interfacing (UART, USB, GPIO, ADC)  
- **Power Systems:** Battery charging, voltage regulation, and load-sharing design  
- **System Integration:** Combining modem, MCU, and power management into a cohesive embedded system  

---

## ⚙️ Technologies & Components
- **MCU:** STM32 L4 Series
- **Modem:** Quectel EC25-AF  
- **Power:** USB-C input, Li-ion battery, charger IC (TP4056 / BQ2407x)  
- **Communication:** USB, UART, CAN 
- **Tools:** KiCad, STM32CubeIDE
