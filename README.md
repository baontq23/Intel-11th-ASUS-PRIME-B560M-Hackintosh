# ASUS-PRIME-B560M-A-Hackintosh
Hackintosh Asus Prime B560M-A + I5-10400 + RX5600XT

<p align="center">
    <a href="https://www.apple.com/macos/monterey/">
        <img src="https://img.shields.io/badge/Monterey-12.6-purple"></a>
    <a href="https://github.com/acidanthera/OpenCorePkg">
        <img src="https://img.shields.io/badge/OpenCore-0.8.8-blue"/></a>
</p>

<p align="center">
    <a href="">
        <img src="https://i.imgur.com/dbjjcw8.png" alt="B560M Hackintosh"> </a>
</p>

# Features

| Feature                              | Status | Dependency          |
| :----------------------------------- | ------ | ------------------- |
| iCloud, iMessage, FaceTime           | ✅   | Whitelisted Apple ID, Valid SMBIOS  |
| AirDrop                              | ✅   | Native  |
| Audio                                  | ✅   | `AppleALC.kext` with Layout ID = 12   |
| WiFi                                 | ✅   | Native  |
| Bluetooth                            | ✅   | Native  |
| Ethernet                             | ✅   | `IntelMausi.kext`  |
| USB 2.0, USB 3.0, Type-C                   | ✅   | `USBToolBox`    |


# Specification

| Category  | ASUS-PRIME-B560M-A       |
| --------- | ------------------------ |
| CPU       | Intel Core i5-10400      |
| SSD       | Samsung 970 EVO PLUS 1TB    |
| RAM       | 16GB DDR4 2666 Mhz       |
| AUDIO     | ALC897      |
| LAN       | Intel I219-V      |
| GPU       | SAPPHIRE PULSE RX 5600 XT 6GB |
| WiFi & BT | BCM94360CS2   |

## Read these before you start:

- [dortania's Hackintosh guides](https://github.com/dortania).
- [dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/).
- [dortania's OpenCore Post Install Guide](https://dortania.github.io/OpenCore-Post-Install/).
- [dortania/ Getting Started with ACPI](https://dortania.github.io/Getting-Started-With-ACPI/).
- [dortania/ opencore `multiboot`](https://github.com/dortania/OpenCore-Multiboot).
- [dortania/ `USB map` guide](https://dortania.github.io/OpenCore-Post-Install/usb/).
- `Configuration.pdf` and `Differences.pdf` in each `OpenCore` releases.

## Wi-Fi CARD
My Wi-Fi card is BCM94360CS2, you need to get a NGFF card like this one.

<p align="center">
    <a href="">
        <img src="https://i.imgur.com/qnRNLmP.jpg" alt="B560M Hackintosh" width="400"> </a>
</p>

# Credits

- [Apple](https://www.apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for all the kexts/utilities that they made.
- [Rehabman](https://github.com/RehabMan) and [Daliansky](https://github.com/daliansky) for the patches and guides and kexts.
- [Dortania](https://github.com/dortania) for for the OpenCore Install Guide.
