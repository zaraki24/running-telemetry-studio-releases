# Running Telemetry Studio

Running Telemetry Studio is a Windows desktop application for synchronizing running FIT telemetry with camera video and exporting transparent HUD overlays.

## Download

Download the latest version from the **Releases** section.

## Supported platform

- Windows 10 / 11 x64

## Before first use

Run `RTS_CHECK_ENV.cmd` first.

It checks whether compatible FFmpeg and FFprobe are available and can install them automatically through Windows Package Manager when needed.

## Current V1 features

- FIT activity import
- Video preview and synchronization
- Metadata Sync
- Manual Absolute Sync
- Running telemetry HUD
- QuickTime Animation / qtrle export
- ProRes 4444 export
- Multi-clip batch export
- Project save / open

## Important

The current Windows installer is unsigned and may show an Unknown Publisher or SmartScreen warning.

Do not disable Windows Defender, Smart App Control, WDAC, or enterprise security policies to run the application.

## Testing feedback

When reporting a problem, please include:

- RTS version
- Windows version
- FIT source/device
- Video camera/device
- Video codec, resolution and frame rate if known
- Screenshot or description of the problem

Please keep the original FIT/video files when an issue occurs. Re-encoding or editing the files may remove metadata needed for debugging.
