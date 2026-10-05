# AoS Combat Roller

A phone-friendly dice roller for Warhammer Age of Sigmar. Roll big pools of D6, sort out fails and crits, and carry results from hit to wound to save to ward.

Tap **Army** to paste a list from Sigdex or the Warhammer app. The roller looks up each unit's weapons and fills in attacks, hit, wound, damage and crit abilities for you.

Unit stats are downloaded when you load a list, from the community [BSData Age of Sigmar 4th edition data](https://github.com/BSData/age-of-sigmar-4th). They can lag behind new rules, so double-check anything that looks off.

## Install it as an app

Open the GitHub Pages site on your phone, then:

- **iPhone (Safari):** tap Share, then **Add to Home Screen**.
- **Android (Chrome):** tap the menu, then **Install app** (or accept the install prompt).
- **Desktop (Chrome or Edge):** click the install icon in the address bar.

After the first visit the roller works offline. Load your army list once while you have signal, and it stays saved on the device.

When you change `index.html`, bump `VERSION` in `sw.js` so installed copies pick up the new files.
