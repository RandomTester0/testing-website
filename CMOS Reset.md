---
title: CMOS Reset
layout: page
parent: Guides
nav_order: 3
---


# 🔁 Quick Guide: How to Reset the CMOS Battery

Resetting the CMOS can help fix unusual BIOS behavior, clear forgotten settings, or restore factory defaults.

---

## 🛠️ Option 1: Remove the CMOS Battery

1. **Shut down your PC completely.**
2. **Unplug the power cord** from the wall outlet or surge protector.
3. **Open the case** and locate the CMOS battery — a small, silver coin-cell battery (CR2032) on the motherboard - and remove the CMOS battery. 
   > 🔧 *Hint: You can use a non-metallic tool like a toothpick or a plastic spudger to carefully pop it out.*
4. **Press and hold the power button** on the case for **3 seconds** to discharge any remaining power.
5. **Reinsert the CMOS battery** into its socket, ensuring it clicks into place.
6. **Plug the power cord back in** to the wall.
7. **Turn the PC on.**

---

## 🔧 Option 2: Use the Clear CMOS Pins

1. **Shut down your PC completely.**
2. **Turn off the PSU** using its switch and **unplug it** from the wall.
3. **Locate the Clear CMOS pins** on your motherboard, typically labeled `JBAT`, `CLRCMOS`, or `CLRTC`.  
   > 📘 *Check your motherboard manual for the exact name and location.*
4. **Touch and hold a metal screwdriver** across both pins for **10 seconds**, then remove it.
5. **Plug the PSU back in**, turn it on, and **boot the PC**.

---

> 💡 After a CMOS reset, your BIOS settings will revert to defaults. You may need to reconfigure boot order or enable features like virtualization.
