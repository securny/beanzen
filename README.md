# BeanZen - Android releases

BeanZen is a coffee brewing app for Bluetooth kitchen scales: live weight, dose,
brew timer, flow rate, brew ratio and charts on a single screen. This repository
publishes Android builds on the Releases page only; the source code is not published.

## Install

1. Download the latest `BeanZen-YYMMDD.apk` from
   [Releases](https://github.com/securny/beanzen/releases).
2. On the phone, allow installation from unknown sources for your browser or
   file manager, then open the APK.
3. Grant the Bluetooth permission when asked - it is the only permission the app
   requests, used solely to connect to the scale.

Builds are signed with a development key. If a previous build refuses to update
(`INSTALL_FAILED_UPDATE_INCOMPATIBLE`), uninstall the old one first.

## Releases

| Release | Date | Notes |
|---|---|---|
| [BeanZen-260910](https://github.com/securny/beanzen/releases/tag/260910) | 2026-09-10 | Acaia timer button fix. Pressing the scale's timer button after pausing the brew in the app now resumes both timers (the app re-starts the scale timer after a short delay - the scale loses an immediate start). A scale-side reset while the brew is running now pauses the app instead of wiping the brew. |
| [BeanZen-260909](https://github.com/securny/beanzen/releases/tag/260909) | 2026-09-09 | First published build. 17 scale models: Acaia Pearl, TIMEMORE Dot, Futula/LFScale CK811, KP2048B and Xiaomi HOTO tested on hardware; Acaia Lunar/Pyxis/Cinco, Atomax Skale II, BOOKOO Themis, Decent Scale, Half Decent, EspressiScale, DiFluid Microbalance/Ti, DIY Coffee Scale, Eclair, Eureka Precisa, Felicita Arc, IKAPE A01, INSMART 863A, Tencent (DSD TECH), TIMEMORE Basic 3, TIMEMORE Black Mirror, Varia AKU, WeighMyBru by published protocol - feedback welcome. Scale timer runs in sync with the app; on Acaia, Decent and Varia the scale's timer button controls the brew. |

## Feedback

Open an issue in this repository and name your scale model.
