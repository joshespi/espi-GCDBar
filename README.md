# GCDBar

A global cooldown bar for World of Warcraft (Retail and WoW Forever). It turns green when you're inside the spell queue window, and prints the % of each fight your GCD sat idle.

![GCDBar during a global cooldown](media/screenshot.png)

## Install

Install from CurseForge, or copy the `GCDBar` folder into `Interface/AddOns/` under `_retail_` or `_forever_`.

## Commands

Everything below is also in the settings panel: `/gcd options`, or click GCDBar in the addons menu by the minimap (right-click there to lock or unlock).

| Command                                | Effect                                          |
| -------------------------------------- | ----------------------------------------------- |
| `/gcd unlock`                          | Show the bar so you can drag it                 |
| `/gcd lock`                            | Lock it in place                                |
| `/gcd size <w> <h>`                    | Set the size                                    |
| `/gcd alpha <0.1-1>`                   | Set the opacity                                 |
| `/gcd colorblind`                      | Blue instead of green in the queue window       |
| `/gcd idle`                            | Toggle an empty bar in combat                   |
| `/gcd hide <combat\|vehicle\|mounted>` | Hide out of combat, in vehicles or mounted      |
| `/gcd report [on\|off\|<sec>]`         | Chat report after fights, or its minimum length |
| `/gcd stats [reset]`                   | Last, average and best of your last 10 fights   |
| `/gcd reset`                           | Default position and size                       |
| `/gcd options`                         | Open the settings panel                         |

## Staying up to date

[`interface-update.yml`](.github/workflows/interface-update.yml) checks Blizzard's version servers daily. When Retail or WoW Forever gets a new patch, it bumps `## Interface` in the TOC, tags a patch release and runs the CurseForge release, so the addon doesn't show as out of date. If `main` has unreleased commits at that point, it commits the bump without releasing and fails the run, so you get an email to tag a release yourself.
