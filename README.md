# pcileech-wifi-interrupts
device just got recently hit by vgk, so i'm sharing this source with u all.
has working legacy interrupts based on ekknod's pcileech-wifi, find a new device using legacy interrupts and enjoy

### Fix for unrecognized driver

1. **Open Device Manager**:
   - Press `Win + X` and select **Device Manager** from the menu.

2. **Locate the Network Controller**:
   - In the Device Manager window, look for **Network Controller** under the **Network Adapters** section (or check for an unidentified device if the driver isn't installed).

3. **Update the Driver**:
   - Right-click on **Network Controller** and select **Update Driver**.

4. **Choose Manual Installation**:
   - Click **Browse my computer for drivers**.
   - Select **Let me pick from a list of available drivers on my computer** (usually found at the bottom of the next screen).

5. **Wait for the Driver List to Load**:
   - The system may take a moment to display the complete list of available drivers. Be patient.

6. **Select the Correct Manufacturer**:
   - In the list of manufacturers, choose **Qualcomm Atheros Communications Inc.**.

7. **Pick the Correct Driver Model**:
   - Look for **Qualcomm Atheros AR9285 Wireless Network Adapter** in the list of available drivers and select it.

8. **Install the Driver**:
   - Follow the on-screen instructions to complete the installation process.

Once the installation is finished, your device should recognize and use the updated driver.

![image](https://github.com/user-attachments/assets/098e2e16-345d-4843-9df8-c43d38d8e2e5)
