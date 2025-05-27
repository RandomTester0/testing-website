---
title: Fix GPU Drivers
layout: page
parent: Guides
nav_order: 4
---

# 🎮 Quick Guide: How to Fix GPU Driver Issues

Reinstalling your GPU drivers properly can fix crashes, black screens, performance issues, and failed updates. Follow these steps to do a clean install using DDU (Display Driver Uninstaller.

---

## 🧰 Step 1: Download the Tools

1. **Download Display Driver Uninstaller (DDU)**  
   📥 [Download DDU from Guru3D](http://www.guru3d.com/files-details/display-driver-uninstaller-download.html)

2. **Download the latest driver** for your GPU from the official page:
   - [🔗 NVIDIA](https://www.nvidia.com/Download/index.aspx)  
     > 💡 *Alternatively, NVIDIA users can use [**NVCleanstall**](https://www.techpowerup.com/download/techpowerup-nvcleanstall/) for a cleaner, debloated install.*
   - [🔗 AMD](https://www.amd.com/en/support)
   - [🔗 Intel](https://www.intel.com/content/www/us/en/download-center/home.html)

> 🚫 **Do not run DDU or install the new driver yet.**

---

## 🧯 Step 2: Boot into Safe Mode

To safely remove your GPU drivers, you need to boot Windows into **Safe Mode**:

1. Click the **Start Menu**, then the **Power icon**.
2. **Hold the Shift key** and **click Restart** (keep holding Shift until you can see the "Please Wait" dialogue instead of "Restarting").
3. Select:
   - `Troubleshoot`
   - `Advanced Options`
   - `Startup Settings`
   - Click `Restart`
4. Once options appear, **press 4** or **F4** to boot into **Safe Mode**.

---

## 🧹 Step 3: Use DDU to Uninstall Drivers

1. **Launch DDU** inside Safe Mode.
2. Select your GPU brand from the drop-down (e.g., NVIDIA, AMD, Intel).
3. Click **“Clean and Restart”**.
   > 🧼 DDU will remove old drivers and reboot your PC automatically.

---

## 🧪 Step 4: Install the Latest Driver

Once back in **normal Windows mode**:

- Run the driver installer you downloaded earlier.

> ✅ After installation, restart your PC to ensure changes take effect.