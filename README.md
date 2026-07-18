<p align="center">
  <img src="images/desktopxr-banner.png" width="1200">
</p>

# Update v1.8.0

Released 1st August 2026

https://www.youtube.com/watch?v=VZTIhLUNZ_A

### FocusCoreAI

- PSVR2 Eye Tracking IPC Path via PSVR2Toolkit.
- DCS QuadView support.
- AMS2 safe shader detection.

### Additional Features and Improvements

- Added web overlay support, including SimHub overlays.
- Added DirectInput support for steering wheels, HOTAS devices, and button boxes.
- Added Discord chat to the HUD. Invite only.
- Added removable and reorderable HUD tiles.
- Improved the positioning system and made cycling through overlays easier.
- Added benchmarking mode, allowing a key or button to start capturing FPS and frame times.
- Prioritised game performance over overlay performance.
- Improved HUD performance while active.
- Fixed a Desktop Overlay crash caused by repeated toggling.
- Fixed `DesktopXR-DataBridge.exe` hanging on exit.
- Reorganised the settings in `DesktopXR.ini`.

---

# DesktopXR

DesktopXR is an OpenXR API layer that renders a desktop overlay in VR using DirectX 11 or DirectX 12.  
It is designed to be lightweight, easy to install, and compatible with standard OpenXR runtimes.

This app will always remain free 🙂

Trailer 2 - https://www.youtube.com/watch?v=3naGEVUOVRc
<br>Trailer 1 - https://www.youtube.com/watch?v=vFJsn9qUZ2g

---

## Features

- OpenXR API layer desktop overlay
- DirectX 11 & 12 rendering
- Heads up Display
- FOV Cropping
- FocusCore Fixed and Eye-tracked foveated rendering
- VisionCore Image Processing
- Minimal performance overhead
- Simple MSI installer
- Clean uninstall support
- No external runtime dependencies

---

## Installation

1. Download the latest `.msi` from the Releases page
2. Run the installer
3. Restart any running OpenXR applications

The API layer will automatically register with the system.

---

## Uninstall

Use standard Windows uninstall:

Settings → Apps → Installed Apps → DesktopXR → Uninstall

or

Control Panel → Programs and Features

---

## Configuration

DesktopXR can be configured via a simple settings file.

To change the overlay toggle key and other options,
see the full documentation:

📖 https://github.com/glenimp617/desktopxr/wiki

---

## Compatibility

- Windows 10 / Windows 11
- OpenXR compatible runtimes
- DirectX 11 capable GPU

---

## Known Limitations

- Tested on standard desktop OpenXR runtimes
- Behavior may vary across headset vendors

---

## License

DesktopXR is distributed as a binary under a proprietary license. See `LICENSE.txt` for details.

This repository and its contents are not licensed for reuse, modification, redistribution, or commercial use unless permission is granted in `LICENSE.txt` or by written agreement.

DesktopXR includes or uses third-party components, including the Khronos OpenXR SDK, NVIDIA NVAPI SDK, and Chromium Embedded Framework. These components remain under their respective licenses. See `THIRD_PARTY_NOTICES.txt` for details.

---

## Disclaimer

This software is provided as-is without warranty.
Use at your own risk.

---

## Support

Bug reports and feedback are welcome via GitHub Issues.
