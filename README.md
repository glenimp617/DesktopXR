<p align="center">
  <img src="images/desktopxr-banner.png" width="1200">
</p>

### Update v1.9.0 - Now in development

Building on the foundations of FocusCore, v1.9.0 will deliver further stability and performance improvements. FocusCore is now graphics-mode agnostic by design, working seamlessly across MSAA, DLSS, and FSR settings without mode-specific configuration.
<br><br>This release will focus exclusively on refining and strengthening FocusCore.  My mission is to get FocusCore to a point where it works on any headset, in any game, at any resolution, with any graphics setting to give you the maximum gpu gains.
<br>

<p align="center">
<a href="https://raw.githubusercontent.com/glenimp617/DesktopXR/main/images/ams2-190.png">
 <img src="https://raw.githubusercontent.com/glenimp617/DesktopXR/main/images/ams2-190.png" width="400">
</a>
  <br>Automobilista 2 - Bigger gains are still to come ;-)
</p>

### Upcoming v1.8.1 - Released on Early Access
https://www.youtube.com/watch?v=duwfWsuPT_U

Sponsors recieve early access - email desktopxr@gmail.com for download link

### DesktopXR
- Desktop Overlay can now be curved!
- Multi-monitor switching is no longer gated behind **Select Overlay**
- Single overlays can now be repositioned without first pressing **Select Overlay**
- Status indicator for FocusCore
- Improved FocusCore logging in `DesktopXR.log` to aid troubleshooting
- Fixed FPS measurement jitter in HUD

### Configurator
- Added support for HOTAS toggle switches
- Added Eye Tracking section
- GUI tiles can now be used with DesktopXR even when no input is bound
- Improved logging in `DesktopXR-Configurator.log` to include device names

---

# DesktopXR

DesktopXR is an OpenXR API layer that renders a desktop overlay in VR using DirectX 11 or DirectX 12.  
It is designed to be lightweight, easy to install, and compatible with standard OpenXR runtimes.

This app will always remain free 🙂

Trailer v1.8.0 - https://www.youtube.com/watch?v=VZTIhLUNZ_A
<br>Trailer 2 - https://www.youtube.com/watch?v=3naGEVUOVRc
<br>Trailer 1 - https://www.youtube.com/watch?v=vFJsn9qUZ2g

## Features

- OpenXR API layer
- DirectX 11 & 12 rendering
- Desktop Overlay
- Heads up Display
- FOV Cropping
- FocusCore Fixed and Eye-tracked foveated rendering
- VisionCore Image Processing
- Web Overlays
- Benchmarking
- Minimal performance overhead
- Simple MSI installer
- Clean uninstall support
- No external runtime dependencies
- SSL malware scanned and binary code signed

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

---

## ❤️ Sponsors

Thank you to everyone supporting DesktopXR!

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/rshummel75">
        <img src="https://github.com/rshummel75.png" width="60" height="60"><br>
        <sub><b>rshummel75</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/phoenixMag00">
        <img src="https://github.com/phoenixMag00.png" width="60" height="60"><br>
        <sub><b>phoenixMag00</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/1650singh">
        <img src="https://github.com/1650singh.png" width="60" height="60"><br>
        <sub><b>1650singh</b></sub>
      </a>
    </td>
  </tr>
</table>
