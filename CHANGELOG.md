# GCDBar

## 1.2.0

- Supports WoW Forever (1.60.1) and Retail 12.1.5, plus the 12.1.7 PTR.
- The interface version now updates automatically with each game patch, so GCDBar shouldn't show as out of date.
- Opens from the addons menu by the minimap: left-click for settings, right-click to lock or unlock.
- "Lock bar" option in the settings panel.
- `/gcd lock` and `/gcd unlock` confirm in chat.
- More resilient to API changes: an event or function missing from a client no longer stops the addon from loading.

## 1.1.0

- `/gcd stats` now keeps your last 10 fights and shows the last, the average and the best. `/gcd stats reset` clears them.
- `/gcd report` turns the end-of-fight chat line on or off, or sets a minimum fight length.
- Settings panel (`/gcd options`) with size, opacity, visibility and report options.
- Opacity (`/gcd alpha`) and a color-blind friendly blue queue color (`/gcd colorblind`).
- Hide the bar out of combat, in vehicles or while mounted (`/gcd hide`).
- `/gcd size` clamps to sane limits and confirms; `/gcd reset` confirms.
- The spell queue window is now read only when it changes.
- The bar refreshes after loading screens.

## 1.0.0

- First release.
- GCD bar that turns green inside your spell queue window.
- Reports the % of each fight your GCD sat idle (`/gcd stats`).
