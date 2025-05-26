---
title: Entering BIOS
parent: Guides
nav_order: 2
---

# 🖥️ How to Enter UEFI/BIOS: A Step-by-Step Guide

Accessing the UEFI/BIOS is useful for configuring system settings like boot order, enabling virtualization, or updating firmware. Below are two common ways to enter the UEFI/BIOS.
> 💡 **Quick Tip:** If your BIOS seems to be corrupted and/or causing issues, try resetting the CMOS battery. This will restore BIOS settings to factory defaults, all prior data will be lost. You can find that guide [here](https://github.com/RandomTester0/guides/blob/main/CMOS%20Reset.md)

---

## 🔧 Option 1: Use the BIOS Key During Startup

### Steps:
1. Completely **shut down** your computer.
2. Power it back on.
3. Immediately and repeatedly **press the BIOS key** (every second or so) until the BIOS screen appears.

### Common BIOS Keys:
| Manufacturer | BIOS Key      |
|--------------|---------------|
| Dell         | F2            |
| HP           | ESC or F10    |
| Lenovo       | F1 or F2      |
| ASUS         | F2 or DEL     |
| Acer         | F2 or DEL     |
| MSI          | DEL           |
| Toshiba      | F2 or ESC     |

---

## 🪟 Option 2: Use Advanced Startup in Windows

If your PC boots too quickly or you prefer not to use the BIOS key, you can access the UEFI/BIOS through Windows itself.

### Method 1: Shift + Restart
1. Hold down the **Shift** key on your keyboard.
2. While holding Shift, click the **Restart** option from the Start Menu (Power → Restart).
3. After your PC restarts, choose:
   - **Troubleshoot** → **Advanced options** → **UEFI Firmware Settings** → **Restart**.

### Method 2: Through Settings
1. Open the **Start Menu**.
2. Go to **Settings** → **System** → **Recovery**.
3. Under *Advanced startup*, click **Restart now**.
4. On the blue screen that appears, choose:
   - **Troubleshoot** → **Advanced options** → **UEFI Firmware Settings** → **Restart**.

> 📝 Note: These methods only work on systems with UEFI firmware.

