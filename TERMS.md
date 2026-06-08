# DesktopXR Terms of Service

**Last updated:** 8 June 2026

These Terms of Service govern your use of DesktopXR, including the DesktopXR installer, application components, OpenXR API layer, companion tools, configuration tools, integrations, documentation, and related software.

By downloading, installing, enabling, or using DesktopXR, you agree to these Terms. If you do not agree, do not use DesktopXR.

## 1. About DesktopXR

DesktopXR is a Windows-based OpenXR and desktop companion software package.

The packaged DesktopXR MSI may include, among other components:

- **DesktopXR.dll**, an OpenXR API layer used to provide DesktopXR runtime functionality;
- **DesktopXR-DataBridge.exe**, a local shared-memory writer used to provide system, application, integration, or telemetry data to DesktopXR components;
- **DesktopXR-Companion.exe**, an OpenXR session loader;
- **DesktopXR-Configurator.exe**, a graphical configuration tool used to manage DesktopXR settings.

DesktopXR is designed to run locally on the user’s Windows PC and provide OpenXR-related desktop, HUD, overlay, telemetry, configuration, and integration features.

## 2. Local Operation

DesktopXR is intended to operate locally on the user’s Windows PC.

DesktopXR may read local system information, local application state, configuration settings, or integration data in order to provide its features. DesktopXR may use local shared memory so that DesktopXR components can exchange information on the same Windows PC.

Unless otherwise stated, DesktopXR does not require users to install or host a server, operate a web service, or add a bot to any third-party platform.

Some optional features may require access to local applications, local APIs, third-party services, or user-authorized integrations.

## 3. OpenXR API Layer

DesktopXR includes an OpenXR API layer component.

The OpenXR API layer may interact with OpenXR runtimes, OpenXR applications, graphics APIs, display-related systems, overlays, and related runtime behaviour in order to provide DesktopXR functionality.

OpenXR runtimes, applications, games, drivers, and graphics APIs are controlled by their respective developers and providers. DesktopXR does not guarantee compatibility with every OpenXR runtime, OpenXR application, game, simulator, driver, headset, or system configuration.

Users are responsible for enabling, disabling, and configuring the DesktopXR OpenXR API layer appropriately for their own system.

## 4. Configuration

DesktopXR may use local configuration files to store user preferences and feature settings.

DesktopXR runtime settings may be managed through DesktopXR-Configurator.exe or by editing the relevant local configuration file directly.

DesktopXR-DataBridge.exe uses its own local configuration file, **DesktopXR-DataBridge.ini**, for DataBridge-specific settings, including optional integration settings.

Users are responsible for ensuring that their DesktopXR configuration is suitable for their own system, applications, hardware, and intended use.

## 5. DataBridge and Shared Memory

DesktopXR-DataBridge.exe is a local companion process that may collect, read, or calculate information from the user’s Windows PC, local applications, local APIs, or authorized integrations.

DataBridge may write this information to local shared memory so that other DesktopXR components, including the DesktopXR OpenXR API layer, can use it for local display or functionality.

DataBridge uses **DesktopXR-DataBridge.ini** for its own settings.

DataBridge is not intended to operate as a remote server.

## 6. DesktopXR Companion

DesktopXR-Companion.exe is an OpenXR session loader included with DesktopXR.

It may be used to start, test, or assist with OpenXR session behaviour for DesktopXR-related workflows.

DesktopXR-Companion.exe operates locally on the user’s Windows PC and is not intended to operate as a remote service.

## 7. DesktopXR Configurator

DesktopXR-Configurator.exe is a graphical configuration tool for managing DesktopXR settings.

The Configurator is provided to make local DesktopXR configuration easier for users. Users may still be responsible for reviewing and understanding the effect of configuration changes before applying them.

## 8. Discord Integration

DesktopXR may include an optional Discord integration.

When enabled, the Discord integration is intended to communicate with the Discord desktop client running locally on the user’s Windows PC using Discord-supported authorization and local RPC mechanisms.

The Discord integration may request permission to access limited Discord information, such as the user’s currently selected voice channel, so that this information can be displayed locally through DesktopXR features such as a HUD or overlay.

The Discord integration is not intended to:

- operate as a Discord bot;
- join Discord servers on behalf of the user;
- send Discord messages;
- moderate Discord servers;
- monitor Discord servers globally;
- collect Discord data for resale or advertising;
- transmit Discord voice-channel information to DesktopXR-controlled servers.

Users remain responsible for complying with Discord’s own terms, policies, and community guidelines when using Discord.

DesktopXR is not affiliated with, endorsed by, sponsored by, or officially associated with Discord Inc.

## 9. Other Third-Party Integrations

DesktopXR may interact with third-party applications, APIs, platforms, runtimes, or services, including but not limited to Discord, OBS, YouTube, OpenXR runtimes, Windows APIs, graphics APIs, hardware drivers, games, simulators, and locally installed applications.

Third-party services and applications are controlled by their respective providers. DesktopXR is not responsible for the availability, behaviour, policies, data handling, or changes made by third-party services.

A third-party provider may change, restrict, or remove access to features that DesktopXR relies on. DesktopXR does not guarantee continued compatibility with any third-party service, API, runtime, application, game, driver, or platform.

## 10. User Responsibilities

You agree to use DesktopXR only in a lawful and responsible manner.

You must not use DesktopXR to:

- violate any applicable law or regulation;
- interfere with, disrupt, or abuse third-party services;
- bypass access controls or platform restrictions;
- collect, monitor, or disclose information in a way that violates the rights of others;
- misuse any API, SDK, local interface, shared-memory interface, or third-party integration;
- tamper with third-party software in a way that violates its terms;
- use DesktopXR in a way that creates security, privacy, or safety risks for others.

You are responsible for ensuring that your use of DesktopXR complies with the terms of any third-party software, platform, runtime, game, simulator, or service that you use with it.

## 11. Software Availability and Changes

DesktopXR may be updated, modified, suspended, or discontinued at any time.

Features may be experimental, incomplete, or subject to change. Some integrations may require approval, authorization, configuration, local application support, or continued access from third-party platforms.

DesktopXR does not guarantee that any feature will remain available, work on every system, or continue to work after changes to Windows, OpenXR runtimes, Discord, OBS, YouTube, graphics drivers, hardware drivers, games, simulators, or other third-party software.

## 12. No Warranty

DesktopXR is provided “as is” and “as available”.

To the maximum extent permitted by law, DesktopXR is provided without warranties of any kind, whether express, implied, or statutory, including but not limited to warranties of merchantability, fitness for a particular purpose, non-infringement, availability, reliability, compatibility, accuracy, or fitness for use with any particular hardware, runtime, game, simulator, or application.

Use DesktopXR at your own risk.

## 13. Limitation of Liability

To the maximum extent permitted by law, DesktopXR and its developers, maintainers, contributors, and distributors will not be liable for any indirect, incidental, special, consequential, exemplary, or punitive damages, or for any loss of data, profits, revenue, goodwill, hardware functionality, software functionality, system availability, configuration, application compatibility, or service access arising from or related to your use of DesktopXR.

This limitation applies whether the claim is based on warranty, contract, tort, negligence, strict liability, or any other legal theory.

## 14. User Data and Privacy

DesktopXR’s handling of data is described separately in the DesktopXR Privacy Policy.

By using DesktopXR, you also agree to the practices described in the Privacy Policy.

## 15. Open Source and Licensing

Certain DesktopXR source code, binaries, documentation, or related materials may be made available under a separate software license.

Where a separate license is provided, that license governs your rights to copy, modify, distribute, or use the relevant software materials. These Terms do not replace or override any applicable open-source license.

If no license is provided for a specific file, release, or component, no additional rights are granted beyond those required to use the software as intended.

## 16. Termination

You may stop using DesktopXR at any time.

DesktopXR access or functionality may be discontinued, limited, or changed if required by technical, legal, security, platform, or third-party service reasons.

Any terms that by their nature should survive termination will continue to apply, including warranty disclaimers, limitations of liability, third-party service disclaimers, and user responsibility provisions.

## 17. Changes to These Terms

These Terms may be updated from time to time.

When changes are made, the “Last updated” date at the top of this page will be revised. Continued use of DesktopXR after changes are published means you accept the updated Terms.

## 18. Contact

For questions about these Terms, support requests, privacy questions, or data deletion requests, contact:

**DesktopXR**  
**Email:** hello@desktopxr.net

Please do not send private tokens, Discord account credentials, or other sensitive authentication information by email.