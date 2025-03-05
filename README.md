

# **DNXtreme AOSP - Modded GSI ROM**  

**⚡ AOSP-based lightweight and optimized GSI ROM**  

## **📌 Features:**  
✔ **Performance Tweaks** – Optimized for smoothness and speed  
✔ **Pre-Installed Essential Apps** – Comes with useful preloaded apps  
✔ **Custom Gaming Mode** – Boost performance while gaming  
✔ **Battery Optimizations** – Improved power efficiency  
✔ **Minimal Bloatware** – Clean and efficient  
✔ **Magisk Compatibility** – Works perfectly with root tweaks  

---

## **📥 Download Links:**  
🔹 **GSI ROM:** [GitHub Releases](https://github.com/DNXtreme/DNXtreme/releases)  
🔹 **Tweaks.apk And Wall.apk Inside The Rom Zip File (Required for Tweaks to Work):** [Download Here](https://github.com/DNXtreme/DNXtreme/releases)  

---

## **📖 Installation Guide:**  

### **🔹 Method 1: Using Custom Recovery (TWRP/OrangeFox)**  
1. **Unzip Rom:** Unzip The Gsi Zip File.  
2. **Backup Data:** Take a full backup before flashing.  
3. **Boot into Recovery:** Use TWRP or any custom recovery.  
4. **Wipe Data:** Wipe **System, Data, Cache, and Dalvik**.  
5. **Flash GSI Image:** Select `Install Image` and flash the `.img` file to **system partition**.  
6. **Flash Magisk ** (Optional) For root access.  
7. **install tweaks.apk and wall.apk from the rom zip**
8. **Reboot & Enjoy!**  

### **🔹 Method 2: Flash via Fastboot (For Non-TWRP Devices)**  
1. **Unzip Rom:** Unzip The Gsi Zip File.  
2. **Enable Developer Options & USB Debugging**.  
3. **Reboot to Fastboot Mode:** (`adb reboot bootloader`)  
4. **Flash GSI Image:**  
   ```sh
   fastboot erase system
   fastboot flash system DNXtremeBase.img
   fastboot -w
   fastboot reboot
   ```  
5. **Boot into System & Set Up Device**.  
6. **install tweaks.apk and wall.apk from the rom zip**
7. **Reboot & Enjoy!**  

---
**Join Telegram :** [@Dnnetworkapp](https://t.me/dnnetworkapp)  

## **📌 Credits:**  
- **Superior OS Team** – For the base ROM  
- **Pixel Experience & LineageOS** – Inspiration & certain patches  
- **All Open-Source Developers** – Contributing to the custom ROM community  

---

## **⚠ Disclaimer:**  
- This is a **modified version of Superior OS** and is **not an official release**.  
- Flashing this ROM **may void your warranty**. Proceed at your own risk!  
- I am **not responsible** for **bricked devices, boot loops, or data loss**. Always take a **backup** before flashing.  
- All trademarks and copyrights belong to their respective owners.  

---

## **📜 Copyright Notice:**  
© **Superior OS & Contributors** – Original base ROM  
© **DNXtreme** – Modifications & Enhancements  

🚀 **Enjoy the ROM and feel free to report any bugs!**  
