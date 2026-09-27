# Ninaivu releases

Ninaivu (Tamil நினைவு, "memory") is a macOS menu bar app for setting a reminder in under two seconds: pull a thread from the menu bar, or type `tea 12m`.

This repository only hosts the downloadable builds. Install with Homebrew:

    brew tap mailbagrahul/ninaivu
    brew trust mailbagrahul/ninaivu
    brew install --cask ninaivu

Or download the zip from the latest release and drag `Ninaivu.app` to Applications.

The app is not yet notarized. On first launch macOS will say it cannot verify the developer: open System Settings › Privacy & Security and click **Open Anyway**.

Requires macOS 14 or later.

## Credits

- **[Noty](https://github.com/aimen08/noty)** by Aymen Hamza ([@aimen08](https://github.com/aimen08)), MIT License — Ninaivu's sticky-notes deck (from 0.4.0) is ported from Noty. Its license ships inside the app (`Ninaivu.app/Contents/Resources/Licenses/`) and is shown in Settings › About.
