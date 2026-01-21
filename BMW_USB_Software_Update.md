# BMW CIC & Combox USB Firmware Updates (UPD01008.bin / UPD05074.bin)

> Officially titled: **BMW Software Update for External Devices – Multimedia and Telephone**


BMW no longer provides these updates on their main site, but they are still accessible from archived CDN links.

---

## 🔧 Files

| File           | Applies To               | BMW System Prefix | Notes                                | Software Update Information |
|----------------|---------------------------|-------------------|--------------------------------------|-------------------------------|
| [`UPD01008.bin`](https://static.bmw.com/content/dam/bmw/staticContent/static_bmw_com/bluetooth/updates/bmw/bin/UPD01008.bin) | CIC Multimedia System     | MX-003.xxxxx      | Improves USB/media/iPod playback     | [`Readme_UPD01008_en.pdf`](https://static.bmw.com/content/dam/bmw/staticContent/static_bmw_com/bluetooth/updates/bmw/pdf/Readme_UPD01008_en.pdf) |
| [`UPD05074.bin`](https://static.bmw.com/content/dam/bmw/staticContent/static_bmw_com/bluetooth/updates/bmw/bin/UPD05074.bin) | Bluetooth / Combox Module | TX-003.xxxxx      | Updates Bluetooth metadata, stability | [`Readme_UPD05074_en.pdf`](https://static.bmw.com/content/dam/bmw/staticContent/static_bmw_com/bluetooth/updates/bmw/pdf/Readme_UPD05074_en.pdf)|

---

## 📦 Installation Instructions

1. Format USB to **FAT32**
2. Copy `.bin` file to the **root directory** of the USB (do not extract or rename)
3. Insert USB into car's port (usually in armrest)
4. Navigate to `Settings → Software Update → Update Software`
5. Follow on-screen prompts

---

## ℹ️ Notes

- These are the final public updates from BMW for CIC/Combox as far as I know.
- But this is for older cars only (cannot define year range though)
- USB may not be recognized immediately - plug it in and drive for a while if needed.
- If iDrive shows "Too old" or "Not supported," the update may be incompatible with your software.
- However, if the update is rejected as "too old", try setting the vehicle's internal date ~10 years earlier, then cycle the ignition and try again.

---

## 🚗 My Case
- BMW 118i of year 2010
- There was a problem that multimedia did not display the song data when music was playing from bluetooth (on Spotify).
- One of these files was installed successfully and this issue was fixed. 
Sometimes it still shows 'unknown' instead of song data, but reconnecting device again helps on those cases. 
- Other file was not recognised as valid after connecting the usb, but still keeping it here as it might be valid for other cars. 

