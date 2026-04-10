# Venta AW730 – LocalTuya Template for Home Assistant

LocalTuya device template for the **Venta AW730 AeroStyle Compact**  
for use with **xZetsubou/hass-localtuya** in Home Assistant.

![Screenshot 1](https://github.com/user-attachments/assets/6f00d363-9b74-4dd4-9f66-e7836a82f7c6)
![Screenshot 2](https://github.com/user-attachments/assets/1cd4f6fc-5314-4fae-a177-312e695e3209)

---

## ✅ Tested Environment

- **Home Assistant**: 2026.4.1 (OS / Core)
- **LocalTuya**: xZetsubou/hass-localtuya
- **Tuya App**: Smart Life
- **Tuya LAN Protocol**: **3.4**
- **Device model**: Venta AW730 AeroStyle Compact
- **Connection**: Wi‑Fi (Tuya / Smart Life)

> ⚠️ Note  
> This template was tested with **Protocol 3.4**.  
> Other protocol versions (3.1 / 3.3) usually **do not work reliably**
> with this device model.

---

## 📦 Included Entities

### 🌫️ Humidifier
- Power on / off
- Target humidity (30–70%)
- Modes:
  - Manual
  - Auto
  - Sleep

### 🌬️ Fan & Device Logic
- Fan speed (1–5)
- Hybrid mode

### 🌡️ Sensors
- Temperature
- Humidity
- PM2.5
- Filter remaining time
- Cleaning remaining time
- Service remaining time
- Water level

### 🎨 LED / Display
- LED on / off
- LED color
- LED brightness

### 🔧 Maintenance & Service
- Filter reset button (not properly tested yet)
- Cleaning reset button (not properly tested yet)
- Service reset button (not properly tested yet)
- RH offset (calibration)

---

## 🧠 Important Notes

- **DP assignments may vary slightly depending on firmware.**
- The Smart Life app should be **closed** while Home Assistant controls
  the device via LocalTuya.
- If sensor values (e.g. temperature) appear incorrect, a **scaling factor**
  may be required (device / firmware dependent).

---

## 🚀 Installation / Usage

1. Install **xZetsubou/hass-localtuya** via HACS
2. Copy template to your /localtuya/templates folder
3. Open LocalTuya → add a new device
4. Enter Device ID, Local Key, and IP address, **Protocol Version: 3.4**
5. In the next dialogue Choose **“Use saved template”**
6. Select this template

Done ✅

---

## 🤝 Community & Contributions

This template was exported from a real, working setup and tested in daily use.  
Feedback, improvements, or reports from other firmware versions are welcome!

If you make changes or improvements:
- feel free to fork the repository
- or submit issues / comments 

---

## 📄 License

MIT – free to use, modify, and redistribute.

---

## 📝 Disclaimer

This template is provided as‑is.  
Use at your own risk.
