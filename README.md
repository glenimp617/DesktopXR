<p align="center">
  <img src="images/desktopxr-banner.png" width="1200">
</p>

# Update 2

https://www.youtube.com/watch?v=X1IDXbnECEI

Work has started on v1.8.0

- Web Overlays — SimHub overlays now supported.
- DirectInput Support — map steering wheels, HOTAS, and button boxes.
- FocusCore support for Pimax OLED headsets.
- Added removable and reorderable HUD tiles.
- Improved positioning system — cycle through overlays more easily.
- Prioritizes game performance over overlays.
- Improved HUD performance when active.
- Fixed Desktop Overlay crash when toggled repeatedly.
- Fixed `DesktopXR-DataBridge.exe` hang on exit.
- Reorganised `desktopxr.ini` settings.

# Update

https://www.youtube.com/watch?v=NftmFZiuGXg

GitHub Issues are temporarily closed while I focus on finishing v1.7.0.
This release has taken longer than expected, but it’s shaping up well. I’m currently aiming for a 1 June release, assuming everything goes to plan.
Issues will remain closed for a couple of weeks afterwards while I take a short break before picking things back up.

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

DesktopXR is distributed as a binary under a proprietary license.
See LICENSE.txt for details.

This product includes components from the Khronos OpenXR SDK
licensed under Apache License 2.0.
See THIRD_PARTY_NOTICES.txt for details.

---

## Disclaimer

This software is provided as-is without warranty.
Use at your own risk.

---

## Support

Bug reports and feedback are welcome via GitHub Issues.
