# Modified BIOS for MSI X99A Gaming Pro Carbon (`MS-7A20`)

- **File:** [`E7A20IMS.140.zip`](./E7A20IMS.140.zip)
- **Base Version:** MSI Official `7A20v14` (`E7A20IMS.140`)
- **Author / Credit:** **DSM2** ([hackintosh-forum.de thread](https://www.hackintosh-forum.de/forum/thread/57364-msi-x99a-gaming-pro-carbon-ventura/?pageNo=8))
- **`E7A20IMS.140` (Raw BIOS) SHA-256:** `172e95f2b84f30401ac5606168ecad7feca9dcf15a8292c5a3e9e471b31e2c9f`
- **`E7A20IMS.140.zip` SHA-256:** `cce9f8b36adc5078098c0c8fdab001ba12686aaa78cac48b55c0b2719df4c1bb`

## Instructions
1. Extract `E7A20IMS.140` from `E7A20IMS.140.zip` to the root of a FAT32-formatted USB stick.
2. Reboot into MSI BIOS Setup and select **M-Flash**.
3. Select `E7A20IMS.140` and wait for the flash process to complete.
4. **Do NOT modify any BIOS settings after flashing** — all macOS-required settings (including hidden `HPET = Disabled` and `CFG Lock = Disabled`) are already stored as the default NVRAM values in `StdDefaults`.
