# Acer Veriton N N4640G Hackintosh – macOS Monterey (OpenCore)

Mini PC build running macOS Monterey using **OpenCore v0.8.8**  
Tested and partially working on the **Acer Veriton N N4640G** with an **Intel® Core™ i3-7100T**

---

## 💻 Hardware Specifications

| Component           | Details                          |
|---------------------|----------------------------------|
| Model               | Acer Veriton N N4640G            |
| Processor           | Intel® Core™ i3-7100T @ 3.4 GHz  |
| RAM                 | 12 GB DDR4-SDRAM                 |
| Storage             | 240 GB SSD (PNY)                 |
| Graphics            | Intel® HD Graphics 630           |
| Networking          | Ethernet LAN (10/100/1000 Mbps) |
| Wireless            | Wi-Fi 5 (802.11ac), Bluetooth 4.0 |
| Power Supply        | 65W                              |
| Color               | Business Black                   |

📄 More details: [IceCat Product Page](https://icecat.biz/en/p/acer/dt.vq0aa.010/veriton-pcs-workstations-n4640g-ci3710ts-53344866.html)

---

## ⚙️ Hackintosh Status

**OS:** macOS Monterey  
**Bootloader:** [OpenCore v0.8.8](https://github.com/acidanthera/OpenCorePkg)

---

### ✅ What's Working

- ✅ Bluetooth  
- ✅ Wi-Fi  
- ✅ CPU power management  
- ✅ Intel UHD 630 hardware acceleration  
- ✅ iMessage, FaceTime, App Store, iTunes Store (⚠️ Generate your own SMBIOS!)  
- ✅ USB ports  
- ✅ DisplayPort  

---

### ⚠️ Known Issues / Not Working

- ❌ Sleep does not work (not debugged due to time constraints — device sold)  
- ❌ VGA port not supported (macOS does not support analog VGA output)

---

## 📝 Notes

- This setup is no longer actively maintained as the mini PC has been sold.  
- Make sure to generate your own **SMBIOS** when replicating this build for services like iMessage and FaceTime to work properly.

---

## 📦 Disclaimer

This repository is for educational and experimental purposes only. Use at your own risk.
