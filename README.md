# BeanZen - Android releases

BeanZen is a coffee brewing app for Bluetooth kitchen scales: live weight, dose,
brew timer, flow rate, brew ratio and charts on a single screen. This repository
publishes Android builds on the Releases page only; the source code is not published.

## Install

1. Download the latest `Beanzen-YYMMDD.apk` from
   [Releases](https://github.com/securny/beanzen/releases).
   Android 12 or newer is required.
2. On the phone, allow installation from unknown sources for your browser or
   file manager, then open the APK.
3. Grant the Bluetooth permission when asked - it is the only permission the app
   requests, used solely to connect to the scale.

Builds are signed with a development key. If a previous build refuses to update
(`INSTALL_FAILED_UPDATE_INCOMPATIBLE`), uninstall the old one first.

## Releases

| Release | Date | Notes |
|---|---|---|
| [Beanzen-261017.2](https://github.com/securny/beanzen/releases/tag/261017.2) | 2026-10-17 | Android 12 fix. On Android 12 the app no longer closes when it connects to a scale. Beanzen now requires Android 12 or newer. |
| [Beanzen-261017](https://github.com/securny/beanzen/releases/tag/261017) | 2026-10-17 | GaggiMate. Add a GaggiMate part to a brewer, enter the machine address and turn on Use for brewing: the brew screen takes weight, pressure, temperature and flow from the machine over Wi-Fi instead of a Bluetooth scale, and after the shot the record is replaced with the machine's shot file. In brew details all channels are on one chart with chips to show or hide each one. Beanconqueror import brings pressure and temperature curves too. LFSmart scales get the current time right after connecting. |
| [Beanzen-261014](https://github.com/securny/beanzen/releases/tag/261014) | 2026-10-14 | Import from Beanconqueror: + in History, pick the export folder or zip, check the preview; coffees, bags, grinders, brewers, water and brews with weight curves and photos are imported, repeated imports add only new records, Override rewrites them. Devices and Water in History are combined into Gear. Info notes for grinders, brewers and water. Fixes: + on every History segment, no empty sheet after returning from a card, elevation 1,800 or 1.800 is read as 1800 m. |
| [Beanzen-261013](https://github.com/securny/beanzen/releases/tag/261013) | 2026-10-13 | History fix. On an empty history segment the search field and the filter capsule no longer shrink into a narrow strip. |
| [Beanzen-261012](https://github.com/securny/beanzen/releases/tag/261012) | 2026-10-12 | Brew history: every brew is saved on RESET or DONE with its weight curve, flow, dose, ratio and time; swipe left to search it and open a brew. Brew details: photo, coffee, brewer and parts, method, grinder with burrs, water, TDS and extraction yield, rating, cupping scores and notes, with catalogs to fill them in. After the brew a panel walks through the details step by step and previews a square image for sharing. Smoother charts; the timer pauses on its own when you lift the cup off the scale. |
| [BeanZen-260910](https://github.com/securny/beanzen/releases/tag/260910) | 2026-09-10 | Acaia timer button fix. Pressing the scale's timer button after pausing the brew in the app now resumes both timers (the app re-starts the scale timer after a short delay - the scale loses an immediate start). A scale-side reset while the brew is running now pauses the app instead of wiping the brew. |
| [BeanZen-260909](https://github.com/securny/beanzen/releases/tag/260909) | 2026-09-09 | First published build. 17 scale models: Acaia Pearl, TIMEMORE Dot, Futula/LFScale CK811, KP2048B and Xiaomi HOTO tested on hardware; Acaia Lunar/Pyxis/Cinco, Atomax Skale II, BOOKOO Themis, Decent Scale, Half Decent, EspressiScale, DiFluid Microbalance/Ti, DIY Coffee Scale, Eclair, Eureka Precisa, Felicita Arc, IKAPE A01, INSMART 863A, Tencent (DSD TECH), TIMEMORE Basic 3, TIMEMORE Black Mirror, Varia AKU, WeighMyBru by published protocol - feedback welcome. Scale timer runs in sync with the app; on Acaia, Decent and Varia the scale's timer button controls the brew. |

## Feedback

Open an issue in this repository and name your scale model.
