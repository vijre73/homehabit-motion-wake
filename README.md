# HomeHabit Motion Wake

A lightweight Android utility that uses the device's front camera to detect motion and automatically bring HomeHabit to the foreground when activity is detected.

## Features

- Detects motion using the tablet's front camera
- Automatically launches or brings HomeHabit to the foreground
- Works while HomeHabit screensaver is active
- Reuses the existing HomeHabit task instead of restarting it
- Optional password-protected web controls on the local network
- Start or stop motion detection directly from the app

## Download

Download the latest version from the **Releases** page.

## Requirements

- Android 5.1 (API 22) or later
- Front-facing camera
- HomeHabit installed (`app.homehabit.view`)
- Camera permission granted

## Installation

### Install APK

1. Download the APK from the Releases page.
2. Open the APK file.
3. Allow installation from unknown sources if prompted.
4. Complete the installation.
5. Launch HomeHabit Motion Wake.
6. Grant camera permission.

### Install Using ADB

```bash
adb install -r HomeHabit-Motion-Wake-1.1.5.apk
```

## How It Works

HomeHabit Motion Wake monitors the device's front camera for motion. When movement is detected, the application brings HomeHabit to the foreground. This allows a tablet to wake up and display a HomeHabit dashboard when someone approaches the device.

The application does not replace HomeHabit and does not manage HomeHabit dashboards, widgets, clocks, weather, or screensavers.

## Tested Device

- Amazon Fire HD Tablet

Compatibility with other Android devices may vary.

## Notes

- Continuous camera monitoring may increase battery usage.
- Motion detection sensitivity depends on lighting conditions.
- Duplicate wake actions are throttled to prevent repeated launches.

## Disclaimer

This project is an independent utility created to work with HomeHabit. It is not affiliated with or endorsed by HomeHabit.

## License

Provided as-is without warranty. Use at your own risk.
