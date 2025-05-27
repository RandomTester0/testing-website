---
title: Entering BIOS
layout: page
nav_order: 3
---

# 🖥️ How to Enter UEFI/BIOS: A Step-by-Step Guide

Accessing the UEFI/BIOS is useful for configuring system settings like boot order, enabling virtualization, or updating firmware. Below are two common ways to enter the UEFI/BIOS.
> 💡 **Quick Tip:** If your BIOS seems to be corrupted and/or causing issues, try resetting the CMOS battery. This will restore BIOS settings to factory defaults, all prior data will be lost. You can find that guide [here](https://randomtester0.github.io/testing-website/CMOS%20Reset.html)

---

## 🔧 Option 1: Use the BIOS Key During Startup

### Steps:
1. Completely **shut down** your computer.
2. Power it back on.
3. Immediately and repeatedly **press the BIOS key** (every second or so) until the BIOS screen appears.

<h3>Common BIOS Keys</h3>
<table>
  <thead>
    <tr>
      <th>Manufacturer</th>
      <th>BIOS Key</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Dell</td><td>F2</td></tr>
    <tr><td>HP</td><td>ESC or F10</td></tr>
    <tr><td>Lenovo</td><td>F1 or F2</td></tr>
    <tr><td>ASUS</td><td>F2 or DEL</td></tr>
    <tr><td>Acer</td><td>F2 or DEL</td></tr>
    <tr><td>MSI</td><td>DEL</td></tr>
    <tr><td>Toshiba</td><td>F2 or ESC</td></tr>
  </tbody>
</table>


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

