# OPlus-AOD-Enabler

A simple module to force enable the All-day Always-On Display (AOD) on OPPO, OnePlus, and Realme devices running Android 15.

---

## ⚠️ Disclaimer

Forcing the Always-On Display to be active 24/7 will lead to **increased battery consumption**. This module modifies system settings, and you should use it at your own risk. The developer is not responsible for any potential issues, including screen burn-in or battery degradation.


## Overview

ColorOS, OxygenOS, and RealmeUI on some devices have removed the option to keep the Always-On Display (AOD) on all day, forcing it into a power-saving mode that turns off after a short period. OPlus might limited this fuctionality by default to avoid potential screen burn-in on some OLED panels within one year, which could save them a damn lot of cash. If your screen got burnt-in within warranty after using this module, congrats on getting a free replacement.

**OPlus-AOD-Enabler** is a module that re-enables this setting. You use the module to set your AOD to all-day, then disable the module, and the setting will stick.

## Requirements

* An OPPO, OnePlus, or Realme device.
* **Android 15**-based firmware (ColorOS, OxygenOS, or RealmeUI).
* A method to flash the module (e.g., Magisk).

## Installation & Usage

Please follow these steps carefully. The module only needs to be active once to apply the setting.

1.  **Flash the Module**: Install the module using your preferred manager (e.g., Magisk) and reboot your device.

2.  **Enable All-Day AOD**:
    * Navigate to `Settings` > `Wallpapers & style` > `Always-On Display`.
    * Enable the **"All-day display"** option.

3.  **Set Your AOD Style**: Choose and customize your preferred AOD clock style, notifications, and other elements.

4.  **Disable the Module (Crucial Step)**:
    * Open your module manager again.
    * **Disable** the OPlus-AOD-Enabler module. Disabling is necessary; do not uninstall it yet if you want to change styles later.

5.  **Reboot**: Restart your phone.

After rebooting, your chosen AOD style will now remain active all day without the module being enabled.

## Compatibility

This module has been successfully tested on the following devices:

* Realme Neo7 Turbo
* Realme GT7(China)

If you have tested this on another device, feel free to create an Issue or Pull Request to update this list.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
