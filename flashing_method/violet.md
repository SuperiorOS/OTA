# Installation Guide — Redmi Note 7 Pro (violet)

> [!WARNING]  
> - Your warranty is void.  
> - All official release builds are tested and safe to use.  
> - If you decide to experiment, mess something up, corrupt your storage, turn your phone into a fancy paperweight, or brick it beyond recovery — **don’t blame us**.  
> - You are doing this at **your own risk** and take full responsibility for anything that may happen.  

> [!NOTE]  
> - The device must have an **unlocked bootloader** and a **recommended custom recovery**.  
> - Make a **full data backup** before flashing.  
> - Ensure your device has at least **30% battery**.  
> - Flash **only** files meant for **Redmi Note 7 Pro (violet)**.  
> - First boot may take 5–10 minutes. Do **not** interrupt or force reboot unless it exceeds 10 minutes.  

---

## Clean Installation

1. Boot into your **custom recovery**.  
2. Flash the **ROM**.  
3. Go to **Wipe → Advanced Wipe**.  
4. Wipe **Data, Dalvik & Cache**.  
5. Reboot back into **Recovery**.  
6. Select **Wipe → Format Data** and type `yes`.  
7. Reboot to **System**.  

---

## Update (Dirty Flash)

> [!NOTE]  
> - Dirty flashing **will not work** for major Android version upgrades  
>   (example: **1.x → 2.x**).  

### Method 1: OTA Update

1. Go to **Settings → System → System updates**.  
2. Download the latest available build.  
3. Tap **Reboot** once the download finishes.  
4. The device will reboot into recovery and install the update.  
5. Reboot to **System**.  

---

### Method 2: Recovery Flash

1. Reboot to **Recovery**.  
2. Select **Install → Choose ROM → Swipe to flash**.  
3. Reboot to **System**.  

---

## Incremental (Delta) Update

> [!IMPORTANT]  
> - Your device **must be on the immediately previous build** to use incremental update.  
> - Example: To install build **B**, your device must already be running build **A** (the build released just before B).  
> - Incremental packages will **fail to install** if the base build does not match.  
> - Do **not** modify system files (root/modules may break the update).  

### Method 1: OTA (Recommended)

1. Go to **Settings → System → System updates**.  
2. Download the **incremental update**.  
3. Tap **Reboot** after download completes.  
4. The device will automatically install the update in recovery.  
5. Reboot to **System**.  

---

### Method 2: Recovery Flash

1. Reboot to **Recovery**.  
2. Select **Install → Choose Incremental Package → Swipe to flash**.  
3. Wait for installation to complete.  
4. Reboot to **System**.  

---

## Support / Bug Reports  

**[Telegram Group](https://t.me/superioros_violet)**
