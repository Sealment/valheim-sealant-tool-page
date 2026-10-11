# Sealant Tool

This mod provides an alternative solution to prevent rain weathering by providing the capability to waterproof tiles with a sealant.

![A swamp shelter with a water sealed roof piece highlighted cyan](https://raw.githubusercontent.com/Sealment/valheim-sealant-tool-page/main/media/swamp-shelter.png)

## Basis

I always found it annoying that in order to avoid degraded wood you had to find a way to place specific roof tiles over objects.
Often I wanted to use wooden floors as unroofed balconies or stairs as windows but the constant need to repair the tiles below was frustrating.

However, Valheim's brutalist philosophy is an appealing part of the gameplay and as such, a 'lore accurate' way to solve the problem was important.
The solution is a water sealant combined with a sealant tool, inspired by the [historical viking approach][massprodtar], utilizing a [pine tar sealant][roskildesealant] for [waterproofing their ships][roskildesealant].
It also fits nicely into the swamp's tier in the progression where you really get to learn the pain of rain.

[roskildesealant]: https://www.vikingeskibsmuseet.dk/en/visit-the-museum/exhibitions/previous-exhibitions/the-reconstructed-ship/exhibition-text/tar
[massprodtar]: https://www.archaeology.wiki/blog/2018/11/07/mass-production-of-tar-may-have-helped-vikings-expansion/

## The items

| | Item | What it does |
|:--|:--|:--|
| ![Water Sealant](https://raw.githubusercontent.com/Sealment/valheim-sealant-tool-page/main/media/WaterSealant.png) | **Water Sealant** | Makes a building piece waterproof. Ferment a **Water Sealant Base** (4 Resin + 2 Guck, at the Mead Ketill) and one base becomes 6 sealant. |
| ![Sealer](https://raw.githubusercontent.com/Sealment/valheim-sealant-tool-page/main/media/Sealer.png) | **Sealer** | The tool. Craft it at a forge (level 2) from 2 Wood and 1 Iron. |

## Use

![Sealing a floor with the Sealer: the piece turns cyan](https://raw.githubusercontent.com/Sealment/valheim-sealant-tool-page/main/media/sealing.gif)

1. Make **Water Sealant Base** at the Mead Ketill from 4 Resin + 2 Guck, then ferment it: one base becomes 6 **Water Sealant**.
2. Craft the **Sealer** at a forge (level 2): 2 Wood, 1 Iron.
3. Equip the Sealer, open its menu (right-click) and pick **Water Seal** or **Strip**.
4. Aim at a building piece and use the Sealer.

- **Water Seal** stops rain and water damage on the piece. It uses one Water Sealant.
- Sealed floors, stairs and corewood also count as roofs for whatever is below them.
- **Strip** removes a piece's sealant. The sealant is not refunded.
- While the Sealer is equipped, unsealed pieces that are viable for sealing glow grey, while the water sealed pieces glow cyan.
- Sealed pieces count for shelter

<p>
<img src="https://raw.githubusercontent.com/Sealment/valheim-sealant-tool-page/main/media/highlight-unsealed.png" height="280" alt="A floor that can be sealed, highlighted grey">
<img src="https://raw.githubusercontent.com/Sealment/valheim-sealant-tool-page/main/media/highlight-sealed.png" height="280" alt="A water sealed floor, highlighted cyan">
</p>

![Two shelters in swamp rain at 20x speed: the left roof weathers, the right one is water sealed](https://raw.githubusercontent.com/Sealment/valheim-sealant-tool-page/main/media/rain-cover.gif)

> Two shelters in the swamp rain, at 20x speed. The roof of the right one is water sealed.

Only player-built Hammer pieces that take rain damage can be sealed.
A piece holds one sealant at a time. Sealing follows the same rules as repairing: the piece's crafting station must be in range, and wards apply.

## Multiplayer

Every player and the server need the mod. The server checks every seal against the world save.

## Configuration

`BepInEx/config/SealantTool.cfg`. The list of pieces that act as roofs is set by the server.
The highlight colors are per player.

## Install and Requirements

- BepInExPack_Valheim
- Jötunn

Use a mod manager (r2modman, Gale or Thunderstore Mod Manager). It installs BepInEx and Jotunn for you.

## AI Disclosure

This mod was made in part by utilizing Anthropic's Claude Opus 5.5.
