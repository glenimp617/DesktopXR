<p align="center">
  ALL SPONSORSHIPS GO TO CANCER RESEARCH UK - <a href="sponsorships/README.md">READ MORE</a>
  <br><a href="https://www.cancerresearchuk.org"><img src="images/canceruk.png" width="1200"></a>
</p>

---

<p align="center">
  <img src="images/desktopxr-banner.png" width="1200">
</p>

# v1.9.0 in development
https://www.youtube.com/watch?v=05yaS6jCjuc (VisionCore) 
<br>https://www.youtube.com/watch?v=JcQB0pbAgeo (FocusCore)

### DesktopXR
- FocusCore Gen2. Intelligent render-lineage system learns how your game renders each eye in real time, automatically applying VRS to compatible workloads while respecting shader exclusions defined in the game's profile.
- VisionCore. High-resolution 8K helmet mask with realistic sunshade effect.
- Eye Tracking. Improved OpenXR path including H/V Offsets (useful for bigscreen beyond 2e).

### Companion
- Handoff & Recall. Launch a game from the companion and automatically return to your desktop when you exit the game.

### Configurator

- Warning System. The configurator automatically checks for common issues and alerts you when something needs attention.
- INI & Temporary Files. Quick access to system configuration, temporary files, and folders.
- Update Notifications. Get notified when a newer version is available.

### DataBridge

- Improved error logging for the CEF Web Renderer.

<br>

<p align="center">
Benchmarks v1.9.0
<br><a href="https://htmlpreview.github.io/?https://github.com/glenimp617/DesktopXR/blob/main/benchmarks/AssettoCorsaEVO-v190.htm">Assetto Corsa Evo MSAA2</a>
<br><a href="https://htmlpreview.github.io/?https://github.com/glenimp617/DesktopXR/blob/main/benchmarks/Automobilista2-v190.htm">Automobilista 2 MSAA2</a>
<br><a href="https://htmlpreview.github.io/?https://github.com/glenimp617/DesktopXR/blob/main/benchmarks/EliteDangerous-v190.htm">Elite Dangerous SMAA</a>
<br><a href="https://htmlpreview.github.io/?https://github.com/glenimp617/DesktopXR/blob/main/benchmarks/Le_Mans_Ultimate-v190.htm">Le Mans Ultimate MSAA2</a>
<br><a href="https://htmlpreview.github.io/?https://github.com/glenimp617/DesktopXR/blob/main/benchmarks/FlightSimulator_2020-v190.htm">Microsoft Flight Simulator 2020</a>
</p>

<br>

<p align="center">
rfactor2 is the first game to run through the new FocusCore without a profile
<br>
<br><a href="https://raw.githubusercontent.com/glenimp617/DesktopXR/main/images/bench-rf2-1.png"><img src="https://raw.githubusercontent.com/glenimp617/DesktopXR/main/images/bench-rf2-1.png" width="400"></a>
<br><a href="https://raw.githubusercontent.com/glenimp617/DesktopXR/main/images/bench-rf2-2.png"><img src="https://raw.githubusercontent.com/glenimp617/DesktopXR/main/images/bench-rf2-2.png" width="400"></a>
<br>rFactor2 MSAA2
</p>

---

# DesktopXR

DesktopXR is an OpenXR API layer that renders a desktop overlay in VR using DirectX 11 or DirectX 12.  
It is designed to be lightweight, easy to install, and compatible with standard OpenXR runtimes.

This app will always remain free 🙂

Trailer 2 - https://www.youtube.com/watch?v=3naGEVUOVRc
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
<br>Sponsors recieve early access - email desktopxr@gmail.com for download link

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
    <td align="center">
      <a href="https://github.com/Letrange-g">
        <img src="https://github.com/Letrange-g.png" width="60" height="60"><br>
        <sub><b>Letrange-g</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/jeffgreenhut">
        <img src="https://github.com/jeffgreenhut.png" width="60" height="60"><br>
        <sub><b>jeffgreenhut</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Nokhz">
        <img src="https://github.com/Nokhz.png" width="60" height="60"><br>
        <sub><b>Nokhz</b></sub>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/jaavib">
        <img src="https://github.com/jaavib.png" width="60" height="60"><br>
        <sub><b>jaavib</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/tgeske88">
        <img src="https://github.com/tgeske88.png" width="60" height="60"><br>
        <sub><b>tgeske88</b></sub>
      </a>
    </td>
  </tr>
</table>
