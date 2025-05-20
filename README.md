# Shadow Clicker 🌑

Shadow Clicker is an advanced Windows auto clicker that can click inside any application window **without moving your mouse**. Perfect for automation tasks, gaming, or any repetitive clicking jobs — all controlled through a sleek PySide6 GUI.

---

## Features

- 🎯 Click inside a target window using native Windows messages (`SendMessageW`), so your mouse cursor stays put  
- 🖱️ Supports single and double clicks  
- 📍 Click at the current mouse position, a custom screen coordinate, or relative inside a specific window  
- ⏱️ Adjustable delay: milliseconds, seconds, and minutes  
- 🔁 Repeat clicks with a configurable count or infinite mode  
- ⌨️ Global hotkey (F8) to toggle clicking on/off  
- 🎯 Easy coordinate picking with Ctrl key  
- 🛑 Safe start/stop controls via GUI or hotkey  

---

## Demo
![dark-demo](https://github.com/user-attachments/assets/ce8b4ed8-1537-4694-9fa4-ddecd2031be0)
![light-demo](https://github.com/user-attachments/assets/3ac45739-62e1-4848-9f2b-66c3f19ee4d9)



---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Bllare/Shadow-Clicker.git
   cd Shadow-Clicker
   pip install -r requirements.txt
   python main.py
   ```
