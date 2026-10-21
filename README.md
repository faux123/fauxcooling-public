# FauxCooling

> **News, help, and the FauxWall beta sign-up are on the [FauxApps Discord](https://discord.gg/ceyPguKNbu).**

A fan controller for Android gaming handhelds. FauxCooling watches how hot the chip is, turns the fan up
as the heat builds, and turns it back down when things cool off. You pick the temperature it aims for.

Free. No ads, no account, and no network permission: the app cannot connect to the internet.

## Download

Get the APK from the [latest release](https://github.com/faux123/fauxcooling-public/releases/latest).

- If you installed FauxCooling from Google Play, uninstall that copy first. The copy here is signed with
  a different key, so Android will not install it over the Play copy.
- Android asks you to allow installs from your browser or file manager the first time.
- Each release lists the file's SHA-256 so you can check your download.

## Devices

| Device | Needs root? | Notes |
| --- | --- | --- |
| AYN Odin 3 | No | Also slows the chip one step at a time if the fan is at full speed and the chip is still too hot. |
| Retroid Pocket 4 Pro | No | Never runs the fan faster than the top setting in the maker's own settings app. |
| Anbernic RG556 | Yes | Stops the fan when the chip is at or below 40 °C, as the device does by itself. |
| GameForce Ace | Yes | Works. Not yet compared against the device's own fan control. |

Other AYN and Retroid Pocket models use the limits in their own thermal tables. Those models have not
been run. Rooted means Magisk, KernelSU, or APatch. On a device where the app cannot get the access it
needs, it says it is not compatible and changes nothing.

More detail, measurements, and screenshots: [fauxcooling.canonspike.com](https://fauxcooling.canonspike.com/).

## Support the app

Every feature is free. If the app is useful to you, you can support the time that goes into it:

- [GitHub Sponsors](https://github.com/sponsors/faux123)
- [Patreon](https://patreon.com/faux123)
- [Ko-fi](https://ko-fi.com/faux123)
- [Buy Me a Coffee](https://buymeacoffee.com/faux123)

## More apps by the same developer

[The full list, with where to get each one](https://fauxapps.canonspike.com/).

Questions and news: the [FauxApps Discord](https://discord.gg/ceyPguKNbu).

## License

FauxCooling is licensed under the Apache License, Version 2.0. This repository holds releases only; the
source is not published. Copyright 2026 Paul Reioux (faux123).

FauxCooling credits O2P Tweaks by FeralAI (GPL-2.0) for first showing how an app can control these
handhelds without rooting them. It contains no code from that project.
