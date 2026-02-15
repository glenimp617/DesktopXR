# DesktopXR

DesktopXR is an OpenXR API layer that renders a desktop overlay in VR using DirectX 11.  
It is designed to be lightweight, easy to install, and compatible with standard OpenXR runtimes.

Version: 1.0.0

---

## Features

- OpenXR API layer desktop overlay
- DirectX 11 rendering
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

## Compatibility

- Windows 10 / Windows 11
- OpenXR compatible runtimes
- DirectX 11 capable GPU

---

## Known Limitations

- Only DirectX 11 rendering is supported
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

This is an early public release (v1.0.0).

Bug reports and feedback are welcome via GitHub Issues.
