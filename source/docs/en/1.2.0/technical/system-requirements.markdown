---
Type:            article
State:           [ obsolete ]
Title:           System requirements
Project:         HandBrake
Project_URL:     https://handbrake.fr/
Project_Version: 1.2.0
Language:        English
Language_Code:   en
Authors:         [ Scott (s55), Bradley Sepos <bradley@bradleysepos.com> (BradleyS) ]
Copyright:       2022 HandBrake Team
License:         Creative Commons Attribution-ShareAlike 4.0 International
License_Abbr:    CC BY-SA 4.0
License_URL:     https://handbrake.fr/docs/license.html
---

System requirements
===================

## Hardware

The following is the minimum level of hardware that HandBrake supports. While it may be technically possible to run HandBrake on hardware older than this, it is neither recommended nor supported.

<!-- .system-linux -->

### Linux

- Processor: Intel Core 2 Duo, AMD Athlon X2, or better
- Free Memory:
  - 256 MB for transcoding standard definition video
  - 1 GB for transcoding high definition video
  - 2 GB or more for transcoding 4K video
- Screen Resolution: 1024x768 or better
- System Storage:
  - 50 MB for the HandBrake app
  - 2 GB or more recommended for processing and storing your new videos

<!-- /.system-linux -->

<!-- .system-macos -->

### Mac

- Processor: Intel Core 2 Duo or better
  - 32-bit Intel Macs (2007 and earlier) cannot run recent 64-bit HandBrake releases
  - 2010 models and newer are recommended, as older Macs are often quite slow for processing video
- Free Memory:
  - 256 MB for transcoding standard definition video
  - 1 GB for transcoding high definition video
  - 2 GB or more for transcoding 4K video
- Screen Resolution: 1024x768 or better
- System Storage:
  - 50 MB for the HandBrake app
  - 2 GB or more recommended for processing and storing your new videos

<!-- /.system-macos -->

<!-- .system-windows -->

### Windows

- Processor: Intel Core 2 Duo, AMD Athlon X2, or better
- Free Memory:
  - 256 MB for transcoding standard definition video
  - 1 GB for transcoding high definition video
  - 2 GB or more for transcoding 4K video
- Screen Resolution: 1024x768 or better (higher if running in High-DPI Mode, above 96 DPI or 100%)
- System Storage:
  - 50 MB for the HandBrake app
  - 2 GB or more recommended for processing and storing your new videos

<!-- /.system-windows -->

HandBrake's QuickSync feature is only supported on Windows. Experimental Linux support requires building from source with `--enable-qsv`. QuickSync requires a 2nd generation (Sandy Bridge) or newer Intel Core series processor with integrated Intel HD Graphics enabled.

## Software

The following describes the level of support available for the current HandBrake version as indicated by the status for each system version.

| Status      | Description                                                                                                                                              |
|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Supported   | HandBrake is tested working on these system versions. The HandBrake Team and community members provide volunteer support, and issue reports are welcome. |
| Deprecated  | HandBrake should work on these system versions. Support is near end of life. Limited functionality and other issues will likely not be addressed.        |
| Unsupported | HandBrake does not work on these system versions. No support will be provided. Please update to enjoy the latest features and bug fixes.                 |

<!-- .system-linux -->

### Linux and BSD

#### Ubuntu (Official PPA)

- Recent Ubuntu LTS versions are generally supported
- HandBrake is typically updated for non-LTS versions until their end of life
- See [Where to get HandBrake](../get-handbrake/where-to-get-handbrake.html) for additional PPA details

| Ubuntu Version     | Status              | Last Compatible Version |
|--------------------|---------------------|-------------------------|
| 18.04 LTS Bionic   | Supported           |                         |
| 16.04 LTS Xenial   | Supported           |                         |
| 14.04 LTS Trusty   | Unsupported         | HandBrake 1.1.2         |

#### Flatpak

Requires a recent Linux distribution and `flatpak` package.

#### Other

For other distributions, compile from source using the [Linux instructions](../developer/build-linux.html) or [BSD instructions](../developer/build-bsd.html).

<!-- /.system-linux -->
<!-- .system-macos -->

### Mac

- macOS 10.10 Yosemite and later
- [VLC](https://www.videolan.org/vlc/) is recommended for previewing/playing MKV (Matroska) media files

| macOS Version      | Status              | Last Compatible Version | Notes                              |
|--------------------|---------------------|-------------------------|------------------------------------|
| 10.14 Mojave       | Supported           |                         | Requires HandBrake 1.1.2 or later. |
| 10.13 High Sierra  | Supported           |                         |                                    |
| 10.12 Sierra       | Supported           |                         |                                    |
| 10.11 El Capitan   | Deprecated in 1.2.0 |                         |                                    |
| 10.10 Yosemite     | Deprecated in 1.2.0 |                         |                                    |
| 10.9 Mavericks     | Unsupported         | HandBrake 1.1.2         |                                    |
| 10.8 Mountain Lion | Unsupported         | HandBrake 1.1.2         |                                    |
| 10.7 Lion          | Unsupported         | HandBrake 1.1.2         |                                    |
| 10.6 Snow Leopard  | Unsupported         | HandBrake 0.10.5        |                                    |

<!-- /.system-macos -->
<!-- .system-windows -->

### Windows

- Windows 7 Service Pack 1 (64-bit) or later
- Microsoft .NET Framework 4.7.1 or later
- [VLC](https://www.videolan.org/vlc/) is recommended for previewing/playing media files

| Windows Version | Status              | Last Compatible Version |
|-----------------|---------------------|-------------------------|
| Windows 10      | Supported           |                         |
| Windows 8.1     | Supported           |                         |
| Windows 7 SP1   | Deprecated in 1.1.0 |                         |
| Windows Vista   | Unsupported         | HandBrake 1.0.7         |
| Windows XP      | Unsupported         | HandBrake 0.9.9         |

<!-- /.system-windows -->
