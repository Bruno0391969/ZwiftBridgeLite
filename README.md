# ZwiftBridgeLite

A lightweight Bluetooth bridge for **Zwift** and **MyWhoosh** on macOS.

ZwiftBridgeLite connects a compatible Bluetooth controller and translates its button presses into keyboard inputs, making it easier to use supported controls while riding.

## Features

- Bluetooth device discovery and connection.
- Support for Zwift and MyWhoosh.
- Automatic RideOn command.
- Controller button mapping:
  - Left / minus button: `I`
  - Right / plus button: `K`
  - `Z` key: `I`
- Clear connection and button status.
- Interface available in 10 languages:
  - Italian, English, German, French, Russian, Chinese, Japanese, Korean, Spanish and Portuguese.
- Simple vertical interface with Connect, Disconnect and Quit controls.

## Requirements

- macOS.
- A compatible Bluetooth controller.
- Zwift or MyWhoosh.

Bluetooth device compatibility may depend on the controller and its firmware.

## Installation

1. Download the latest `ZwiftBridgeLite-Vertical.dmg` from the [GitHub Releases](https://github.com/Bruno0391969/ZwiftBridgeLite/releases) page, when a release is available.
2. Open the DMG.
3. Drag `ZwiftBridgeLite-Vertical.app` to the Applications folder (or use the Applications shortcut in the DMG).
4. Eject the mounted DMG.

## First launch and permissions

macOS may ask you to approve Bluetooth access and the system permissions needed to send keyboard events. Allow the requested permissions in **System Settings → Privacy & Security**.

The current app is locally code-signed and is not notarized by Apple. Depending on your macOS security settings, Gatekeeper may display a warning on first launch.

## Usage

1. Open ZwiftBridgeLite.
2. Select **Search** to discover nearby Bluetooth devices.
3. Select the compatible controller and connect.
4. Check the connection and button status in the app.
5. Start Zwift or MyWhoosh and use the mapped controller buttons.

Use **Disconnect** before removing or changing the controller. Use **Quit** to close the app cleanly.

## Privacy

ZwiftBridgeLite is a local macOS utility. This project does not provide accounts, advertising, in-app purchases or donation links.

## Project status

The macOS vertical build has been tested by the developer with Zwift and MyWhoosh. Compatibility with other controllers and macOS configurations may vary.

## License

No open-source license has been added yet. All rights are reserved by the author unless a license is added to this repository.
