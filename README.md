# The Basic Fantasy RPG Core Rules Foundry Project

## A Content Module for the Foundry VTT

[![GitHub Release](https://img.shields.io/github/v/release/DC23/basicfantasyrpg-corerules-en?label=Release&color=blue&logo=GitHub)](https://github.com/DC23/basicfantasyrpg-corerules-en/releases/latest)
[![Static Badge](https://img.shields.io/badge/Foundry%20Version-9_--_10-orange?logo=foundry-virtual-tabletop)](https://foundryvtt.com/)
[![GitHub Issues](https://img.shields.io/github/issues-raw/DC23/basicfantasyrpg-corerules-en?label=Tasks&logo=GitHub)](https://github.com/DC23/basicfantasyrpg-corerules-en/issues)
[![GitHub Bugs](https://img.shields.io/github/issues-raw/DC23/basicfantasyrpg-corerules-en/bug?logo=GitHub&label=Bugs&color=red)](https://github.com/DC23/basicfantasyrpg-corerules-en/issues?q=is%3Aopen+is%3Aissue+label%3Abug)
![GitHub Total Downloads](https://img.shields.io/github/downloads/DC23/basicfantasyrpg-corerules-en/total?logo=GitHub&label=Downloads)
![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads/DC23/basicfantasyrpg-corerules-en/latest/total?logo=GitHub&label=Downloads%3A%20Latest)

This is a content pack for the [Basic Fantasy RPG system](https://www.github.com/orffen/basicfantasyrpg) for Foundry. It provides content from the book **Basic Fantasy Role-Playing Game Core Rules**, available for free at the [Basic Fantasy Website](https://www.basicfantasy.org/), originally under the [OGL](./LICENSE), and now under the [CC-BY-SA 3.0 International license](https://creativecommons.org/licenses/by-sa/4.0/deed.en).

> [!IMPORTANT]  
> This project has been stalled on older versions of Foundry and the BFRPG 3rd edition for some time.
> In the time since significant work took place on this project, two major changes have taken place:
>
> First, there have been large changes in the Foundry API. The data structures this module relies on have completely changed. Everything now needs to change at the data storage level.
>
> Second, at the start of 2023 there was the great OGL Saga. As a response to this, the BFRPG Community rallied
> in a truly remarkable way, producing the Basic Fantasy Role-Playing Game 4th Edition, under a Creative Commons
> licence. This remarkable feat didn't require many changes to game mechanics, but it did result in significant
> changes to the text. Thus the flow-on changes to this content module are substantial.
>
> This module doesn't need an update.
>
> It needs a complete overhaul.
>
> As a result, updates to Foundry v12 and beyond are being planned in two stages.
>
> 1. The v12 with BFRPG 3e content patch release. This release is aiming to do the barest minimum work required for v12 compatibility, but with the existing OGL BFRPG 3e content. The content will be updated to the new data structures using any means we can find.
> 2. The forward-facing, future-proof rebuilding effort. This is where most of the work will be going. The vision is to reduce the manual data entry required to keep the module updated by attempting to build semi-automated data pipelines. It's experimental, so time will tell how it goes!

## Manual Installation

This module should soon be available directly via FoundryVTT, but it can be manually added by using the manifest link below:

```html
https://github.com/DC23/basicfantasyrpg-corerules-en/releases/latest/download/module.json
```

## Notes on using this module

I recommend ticking "Keep Document ID's" when importing, this will allow the links to RollTables referenced in some of the spell descriptions to work.

## The Compendium Contains

* Equipment
* Weapons
* Armor & Shields
* Spells
* Monsters

## Contributing

Please see the [Contribution Guidelines](./CONTRIBUTING.md).

## Licensing

Note that at present, this module contains BFRPG content licenced under the [OGL](./LICENSE), a copy of which is included in this repository.

## Thanks & Acknowledgements

* The current maintainers of this project wish to extend their thanks to the original project team, without whom this module would not exist!
* Many thanks to [@totallybanjaxed](https://github.com/totallybanjaxed) for laboriously validating and fixing issues with monsters and other items.
* Massive thanks to Solomoriah and the cast of thousands of the Basic Fantasy Project, without whom this project would not be possible.
