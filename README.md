# USBFlow - Public Downloads

This repository contains only the public Windows installer for USBFlow.

Application source: https://github.com/ImEchoCoder/usbflow (GPL-3.0).

Download `USBFlow-0.1.0-beta-setup.exe` from the latest release:
https://github.com/ImEchoCoder/usb-sharing-dist/releases/latest

SHA-256: `8ABAA6665BF5FA604E41E4BCFE16E86638569DBFC48E8DDC1FE187F37225FD8B`

Verify before running:

```powershell
Get-FileHash .\USBFlow-0.1.0-beta-setup.exe -Algorithm SHA256
```

The installer is unsigned; Windows SmartScreen may warn. Choose **More info, then Run anyway** only after the hash matches.

Technician room (license required): the licensed app starts a permanent machine-locked room automatically; there is no Connect button and no code to enter. Up to five customers can join with that code.

Customer / Share is free: enter the technician's code and connect, then toggle USB devices in the live session. Each device shows Available -> Shared -> Under service -> Shared (work done) after the technician detaches.

The technician attaches/detaches USB locally and can Remove one customer at a time; removal returns that customer to Connect and leaves the room and all others connected.

GitHub's "Source code (zip)" links on releases are generated from this repository only and contain no application source.
