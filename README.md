# 🚰 Water Tank Monitoring & Control System

A complete simulation project built using **RSLogix Micro** for PLC Ladder Logic and **FactoryTalk View ME** for HMI interface.

This system simulates automated and manual control of a water tank with alarm and notification handling.

---

## 🎬 Project Demo

[![Watch the demo video](https://img.youtube.com/vi/iIhKhjNIBaA/0.jpg)](https://youtu.be/iIhKhjNIBaA)

---

## 🧠 Features

- Auto / Manual mode switching (HOA)
- Independent control of pump and valve
- Safety lockout when level reaches HH or LL
- Multi-state water level display (Very Low, Low, High, Very High)
- Water level visualization with 4 sensor states
- Alarm banner for HH and LL
- Attention flashing panel for user notifications
- Acknowledge button to silence non-critical alerts

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `WaterTank.ACD` | PLC Ladder Logic file (RSLogix Micro) |
| `WaterTank.MER` | FactoryTalk View ME HMI project |
| `README.md` | Project documentation |


---

## 📊 System Behavior

- When water is low → Pump activates automatically.
- When water is high → Valve opens automatically.
- If water reaches critical levels (HH or LL), system triggers alarm.
- Manual mode allows full control unless blocked by safety logic.

---

## 🧪 Simulation Note

Water level changes are simulated via four switches:
`LL`, `L`, `H`, `HH` — manually toggled in Ladder logic.

---

## 👤 Author

**Alwaleed Abdullah Alzahrani**  
Electrical Engineering Graduate  
📧 alwaleedaldawsi@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/alwaleedalzahrani)
