## Device Firmware Issue & Recovery Guide

### Overview
There was an issue with **firmware version 13.00** (now removed). This issue has been fixed in **version 14.00**.

- Devices updated to **13.00 are not bricked**
- However, they **may not function properly**

---

### Important Recommendation (PV Systems)
If you are using a **PV (solar) system**:

- Power the device **when there is no sunlight**
- This reduces voltage levels
- Helps avoid **overvoltage issues** during inclusion

---

### Voltage Behavior
- Device works normally on **110–120 VAC**
- Overvoltage protection may trigger too early
- It can activate at around **126 VAC**

---

### Recovery Steps

If your device powers on correctly, follow these steps:

1. **Factory Reset**  
   Reset the device to factory settings

2. **Add Device (Non-Secure)**  
   Include the device **without secure inclusion**  
   > Secure inclusion may cause the process to fail

3. **Update Firmware**  
   Update to **version 14.00**  
   - Available on the GitHub repository: `Wave_Plug_US`

---

### Final Steps

After updating:

1. **Exclude the device**
2. **Factory Reset again**

---

### Result
Once completed:

- Device will run **firmware version 14.00**
- Device should **operate normally**
