---
title: Fix Windows Corruption
layout: page
parent: Guides
nav_order: 5
---

# 🛠️ Windows Corruption Repair Guide

This guide will help you fix corruption issues on your Windows PC, starting from the most common solutions and escalating to an in-place repair upgrade if needed.

- Always ensure your data is **backed up** before proceeding with any repair or upgrade process.

---

## Step 1: Run System File Checker to Check for System File Corruption

1. Press `Windows + S` and search for **Command Prompt**.
2. Right-click **Command Prompt** and select **Run as Administrator**.
3. In the Command Prompt window, type:
> sfc /scannow
4. Wait for the process to complete (this can take some time).
5. If any issues are found and repaired, **restart your computer**.

---

## Step 2: Run the DISM Command for Advanced Repair

1. Open **Command Prompt** as an Administrator (same as above).
2. In the Command Prompt window, type:
> DISM /Online /Cleanup-Image /RestoreHealth
3. This command will attempt to fix any corruption related to the system image.
4. Once completed, **restart your computer**, especially if the tool reports that repairs were made.

---

## Step 3: If `sfc /scannow` and `DISM` Do Not Resolve the Issue

If the previous steps did not fix the corruption, proceed with one of the following repair upgrade methods:

### Option 1: Repair Windows via Settings (Windows 11 22H2+)

1. Press `Windows + I` to open **Settings**.
2. Go to **System** > **Recovery**.
3. Under the **Advanced Startup** section, click **Restart now**.
4. When your PC restarts, select **Troubleshoot** > **Advanced options** > **Start-up Repair**.
5. In the **Advanced Startup** menu, there should be an option labeled **Fix problems using Windows Update**, which will automatically check for any required repairs, reinstalling the Windows files while keeping your files and apps intact.
6. Follow the on-screen instructions to complete the process.

### Option 2: In-Place Repair Upgrade Using the ISO File

1. **Check Your Current Windows Version**:
- Press `Windows + R`, type `winver`, and press Enter.
- Note your Windows version (e.g., 22H2 or 21H1) and build number.

2. Download the Windows ISO using the [Microsoft Media Creation Tool](https://www.microsoft.com/software-download/windows10) or [Windows 11 download page](https://www.microsoft.com/software-download/windows11).

3. **Do NOT Burn the ISO to a Disk**:
- After downloading the ISO, **DO NOT burn it** to a USB or DVD.
- Simply **mount the ISO** by double-clicking it or right-clicking and selecting **Mount**.

4. **Run `setup.exe` from the Mounted ISO**:
- In the mounted ISO folder, double-click `setup.exe` to begin the upgrade process.
- Select the option to upgrade to the **same version of Windows** you currently have (check your version using `winver`).
- Follow the on-screen instructions to complete the repair upgrade process.
- Your files and apps will remain intact.

5. Once the upgrade is finished, **restart your computer**.

---

## Step 4: If All Else Fails

If neither of the repair upgrade methods resolves the issue, you may need to perform a clean installation of Windows.

1. Follow the steps in my detailed [Windows Installation Guide](https://randomtester0.github.io/testing-website/Windows%20Install.html).

---

Good luck fixing any issues!