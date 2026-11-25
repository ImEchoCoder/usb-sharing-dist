# USBFlow - Public Downloads

This repository contains only the public Windows installer for USBFlow.

Application source: https://github.com/ImEchoCoder/usbflow (GPL-3.0).

Download `USBFlow-0.1.0-beta-setup.exe` from the latest release:
https://github.com/ImEchoCoder/usb-sharing-dist/releases/latest

SHA-256: `69D68D833F52BF0EE0CFEBBA6308D9A4DAF3ECF3746BB81097C06A0EAD2479C2`

Verify before running:

```powershell
Get-FileHash .\USBFlow-0.1.0-beta-setup.exe -Algorithm SHA256
```

The installer is unsigned; Windows SmartScreen may warn. Choose **More info → Run anyway** only after the hash matches.

Customer / Share is free: enter the technician's code, connect, then toggle USB devices in the live session. Technician / Connect requires a paid 1-year license (one PC, one permanent machine-locked code); attach/detach only changes the device, while **Remove** ends the session for both sides.

GitHub's "Source code (zip)" links on releases are generated from this repository only and contain no application source.
