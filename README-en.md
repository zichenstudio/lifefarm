# LifeFarm

[简体中文](README.md)|[English](README-en.md)

A Minecraft modpack focused on farming, scenery, and a relaxed retirement-style pace, built on top of [Elixir](https://modrinth.com/modpack/elixir).

> Lightweight, relaxed, slow-paced

## Modpack Information
- Minecraft Version: 1.21.11
- Modpack Version: ![version](https://img.shields.io/github/v/release/zichenstudio/lifefarm)
- Mod Loader: Fabric
- Recommended Memory: 8GB

## Usage

### Method 1: Play Directly (Recommended)

Don't want to tinker? Just download the packaged `.mrpack` and drag it into your launcher.

1. Go to [releases](https://github.com/zichenstudio/lifepack/releases/latest)
2. Download the latest `.mrpack` file
3. Drag it into your launcher
4. Configure as needed — see [Configuration Steps](#configuration-steps)

### Method 2: Build from Source

If you want to build your own modpack based on this project, or just prefer to build it yourself.

**Requirements**

You need [packwiz](https://github.com/packwiz/packwiz)

**Build Steps**

```bash
git clone https://github.com/zichenstudio/lifefarm.git
cd lifefarm
packwiz modrinth export
```

After building, the `.mrpack` file will be in the root directory. Follow the steps in [Play Directly](#method-1-play-directly-recommended) to install it.

### Configuration Steps

*(This section is entirely optional — configure according to your own needs.)*

The modpack makes some vanilla-conflicting enchantments compatible, but some are disabled by default.

- If you want damage-type enchantments to be compatible, use the command `/datapack enable "universalenchants:compatible_damage_enchantments"`
- If you want protection-type enchantments to be compatible, use the command `/datapack enable "universalenchants:compatible_protection_enchantments"`

You can also disable them again at any time, but enchanted items will retain their enchantments.

If you don't have a resource pack ready, you can directly enable the Spectral resource pack we've prepared.

That covers the essential information.

## Mod List

| Name | Author | License |
| --- | --- | --- |
|[[EMF] Entity Model Features](https://modrinth.com/mod/entity-model-features)|[Traben](https://modrinth.com/user/Traben)|LGPL-3.0-only|
|[[ETF] Entity Texture Features](https://modrinth.com/mod/entitytexturefeatures)|[Traben](https://modrinth.com/user/Traben)|LGPL-3.0-only|
|[Animatica](https://modrinth.com/mod/animatica)|[FoundationGames](https://modrinth.com/user/FoundationGames)|LGPL-3.0-only|
|[AppleSkin](https://modrinth.com/mod/appleskin)|[squeek502](https://modrinth.com/user/squeek502)|Unlicense|
|[Balm](https://modrinth.com/mod/balm)|[BlayTheNinth](https://modrinth.com/user/BlayTheNinth)|LicenseRef-All-Rights-Reserved|
|[Bedtime / WCIFS](https://modrinth.com/mod/wcifs)|[orb1n](https://modrinth.com/user/orb1n)|CC-BY-NC-SA-4.0|
|[Better Biome Blend](https://modrinth.com/mod/better-biome-blend)|[FionaTheMortal](https://modrinth.com/user/FionaTheMortal)|Unlicense|
|[Better Block Entities](https://modrinth.com/mod/better-block-entities)|[cseden](https://modrinth.com/user/cseden), [Adre278](https://modrinth.com/user/Adre278)|LGPL-3.0-or-later|
|[Better Mount HUD](https://modrinth.com/mod/better-mount-hud)|[Lortseam](https://modrinth.com/user/Lortseam)|GPL-3.0-only|
|[Boat Item View](https://modrinth.com/mod/boat-item-view)|[50ap5ud5](https://modrinth.com/user/50ap5ud5)|LGPL-3.0-only|
|[Carry On](https://modrinth.com/mod/carry-on)|[Tschipp](https://modrinth.com/user/Tschipp)|LGPL-3.0-only|
|[Cloth Config API](https://modrinth.com/mod/cloth-config)|[shedaniel](https://modrinth.com/user/shedaniel)|LGPL-3.0-only|
|[Continuity](https://modrinth.com/mod/continuity)|[Pepper_Bell](https://modrinth.com/user/Pepper_Bell)|LGPL-3.0-only|
|[Controlling](https://modrinth.com/mod/controlling)|[jaredlll08](https://modrinth.com/user/jaredlll08)|MIT|
|[CreativeCore](https://modrinth.com/mod/creativecore)|[creativemd](https://modrinth.com/user/creativemd)|LGPL-3.0-only|
|[CropXP](https://modrinth.com/mod/agricultureplus)|[Hamburgeri and Armi](https://modrinth.com/organization/resistance)|CC0-1.0|
|[Cubes Without Borders](https://modrinth.com/mod/cubes-without-borders)|[Kira-NT](https://modrinth.com/user/Kira-NT)|MIT|
|[Detail Armor Bar Reconstructed](https://modrinth.com/mod/detail-armor-bar-reconstructed)|[Coredex](https://modrinth.com/user/Coredex)|MIT|
|[Durability Tooltip](https://modrinth.com/mod/durability-tooltip)|[SuperMartijn642](https://modrinth.com/user/SuperMartijn642)|LicenseRef-All-Rights-Reserved|
|[Dynamic FPS](https://modrinth.com/mod/dynamic-fps)|[juliand665](https://modrinth.com/user/juliand665), [LostLuma](https://modrinth.com/user/LostLuma)|MIT|
|[Entity Culling](https://modrinth.com/mod/entityculling)|[tr7zw](https://modrinth.com/user/tr7zw), [Pelotrio](https://modrinth.com/user/Pelotrio), [vicisacat](https://modrinth.com/user/vicisacat)|LicenseRef-tr7zw-Protective-License|
|[Fabric API](https://modrinth.com/mod/fabric-api)|[modmuss50](https://modrinth.com/user/modmuss50), [Player7457](https://modrinth.com/user/Player7457)|Apache-2.0|
|[Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin)|[modmuss50](https://modrinth.com/user/modmuss50), [Player7457](https://modrinth.com/user/Player7457)|Apache-2.0|
|[Farmer's Delight Refabricated](https://modrinth.com/mod/farmers-delight-refabricated)|[Cassian](https://modrinth.com/user/Cassian), [MehVahdJukaar](https://modrinth.com/user/MehVahdJukaar), [vectorwing](https://modrinth.com/user/vectorwing)|MIT|
|[Fast IP Ping](https://modrinth.com/mod/fast-ip-ping)|[fallen-breath](https://modrinth.com/user/fallen-breath)|LGPL-3.0-only|
|[FastQuit](https://modrinth.com/mod/fastquit)|[contaria](https://modrinth.com/user/contaria)|MIT|
|[FerriteCore](https://modrinth.com/mod/ferrite-core)|[malte0811](https://modrinth.com/user/malte0811)|MIT|
|[Forge Config API Port](https://modrinth.com/mod/forge-config-api-port)|[Fuzs](https://modrinth.com/user/Fuzs)|MPL-2.0|
|[Fzzy Config](https://modrinth.com/mod/fzzy-config)|[fzzyhmstrs](https://modrinth.com/user/fzzyhmstrs)|LicenseRef-TDL-M|
|[Horseman](https://modrinth.com/mod/horseman)|[mortuusars](https://modrinth.com/user/mortuusars)|MIT|
|[ImmediatelyFast](https://modrinth.com/mod/immediatelyfast)|[RaphiMC](https://modrinth.com/user/RaphiMC)|LGPL-3.0-or-later|
|[Iris Shaders](https://modrinth.com/mod/iris)|[coderbot](https://modrinth.com/user/coderbot), [IMS](https://modrinth.com/user/IMS)|LGPL-3.0-only|
|[ItemPhysic Lite](https://modrinth.com/mod/itemphysic-lite)|[creativemd](https://modrinth.com/user/creativemd)|LGPL-2.1-only|
|[Jade 🔍](https://modrinth.com/mod/jade)|[Snownee](https://modrinth.com/user/Snownee)|CC-BY-NC-SA-4.0|
|[Just Enough Items (JEI)](https://modrinth.com/mod/jei)|[mezz](https://modrinth.com/user/mezz)|MIT|
|[kennytvs-epic-force-close-loading-screen-mod-for-fabric](https://modrinth.com/mod/forcecloseworldloadingscreen)|[kennytv](https://modrinth.com/user/kennytv), [mdcfe](https://modrinth.com/user/mdcfe), [spottedleaf](https://modrinth.com/user/spottedleaf)|MIT|
|[Language Reload](https://modrinth.com/mod/language-reload)|[Jerozgen](https://modrinth.com/user/Jerozgen)|MIT|
|[LibJF](https://modrinth.com/mod/libjf)|[JFronny](https://modrinth.com/user/JFronny)|LGPL-3.0-or-later|
|[Lithium](https://modrinth.com/mod/lithium)|[2No2Name](https://modrinth.com/user/2No2Name), [jellysquid3](https://modrinth.com/user/jellysquid3)|LGPL-3.0-only|
|[Lithostitched](https://modrinth.com/mod/lithostitched)|[Apollo](https://modrinth.com/user/Apollo)|MIT|
|[Locator Heads](https://modrinth.com/mod/locator-heads)|[Haage](https://modrinth.com/user/Haage)|LGPL-3.0-only|
|[Main Menu Credits](https://modrinth.com/mod/main-menu-credits)|[isxander](https://modrinth.com/user/isxander)|LGPL-3.0-only|
|[MixinTrace](https://modrinth.com/mod/mixintrace)|[comp500](https://modrinth.com/user/comp500)|MIT|
|[Mod Menu](https://modrinth.com/mod/modmenu)|[gniftygnome](https://modrinth.com/user/gniftygnome), [modmuss50](https://modrinth.com/user/modmuss50), [Prospector](https://modrinth.com/user/Prospector)|MIT|
|[ModernFix-mVUS](https://modrinth.com/mod/modernfix-mvus)|[Coredex](https://modrinth.com/user/Coredex)|LGPL-3.0-only|
|[More Chat History](https://modrinth.com/mod/morechathistory)|[JackFred](https://modrinth.com/user/JackFred)|CC0-1.0|
|[More Culling](https://modrinth.com/mod/moreculling)|[FX](https://modrinth.com/user/FX), [1Foxy2](https://modrinth.com/user/1Foxy2)|GPL-3.0-only|
|[Mouse Tweaks](https://modrinth.com/mod/mouse-tweaks)|[YaLTeR](https://modrinth.com/user/YaLTeR)|BSD-3-Clause|
|[NBT Autocomplete](https://modrinth.com/mod/nbt-autocomplete)|[mt1006](https://modrinth.com/user/mt1006)|LGPL-3.0-only|
|[No Chat Reports](https://modrinth.com/mod/no-chat-reports)|[Aizistral](https://modrinth.com/user/Aizistral), [robotkoer](https://modrinth.com/user/robotkoer)|WTFPL|
|[Open Parties and Claims](https://modrinth.com/mod/open-parties-and-claims)|[thexaero](https://modrinth.com/user/thexaero)|LGPL-3.0-only|
|[OptiGUI](https://modrinth.com/mod/optigui)|[opekope2](https://modrinth.com/user/opekope2)|LGPL-3.0-or-later|
|[Particle Core](https://modrinth.com/mod/particle-core)|[fzzyhmstrs](https://modrinth.com/user/fzzyhmstrs)|MIT|
|[Polytone](https://modrinth.com/mod/polytone)|[MehVahdJukaar](https://modrinth.com/user/MehVahdJukaar), [gayasslily](https://modrinth.com/user/gayasslily), [Plantkillable](https://modrinth.com/user/Plantkillable)|GPL-3.0-or-later|
|[Presence Footsteps](https://modrinth.com/mod/presence-footsteps)|[Sollace](https://modrinth.com/user/Sollace)|LicenseRef-Polyform-Shield-1.0|
|[Provi's Health Bars](https://modrinth.com/mod/provis-health-bars)|[Provismet](https://modrinth.com/user/Provismet)|LicenseRef-Lily-License-v1.1|
|[Puzzles Lib](https://modrinth.com/mod/puzzles-lib)|[Fuzs](https://modrinth.com/user/Fuzs)|MPL-2.0|
|[Remove Reloading Screen](https://modrinth.com/mod/rrls)|[dima_dencep](https://modrinth.com/user/dima_dencep)|OSL-3.0|
|[Respackopts](https://modrinth.com/mod/respackopts)|[JFronny](https://modrinth.com/user/JFronny)|MIT|
|[Search Stats](https://modrinth.com/mod/searchstats)|[NotRyken](https://modrinth.com/user/NotRyken)|Apache-2.0|
|[Searchables](https://modrinth.com/mod/searchables)|[jaredlll08](https://modrinth.com/user/jaredlll08)|MIT|
|[Server Pinger Fixer](https://modrinth.com/mod/serverpingerfixer)|[JustAlittleWolf](https://modrinth.com/user/JustAlittleWolf)|MIT|
|[ServerAddressSpaceFix](https://modrinth.com/mod/serveraddressspacefix)|[TheWhiteDog9487](https://modrinth.com/user/TheWhiteDog9487)|WTFPL|
|[Shulker Box Tooltip](https://modrinth.com/mod/shulkerboxtooltip)|[MisterPeModder](https://modrinth.com/user/MisterPeModder)|MIT|
|[Sit](https://modrinth.com/mod/bl4cks-sit)|[bl4ckscor3](https://modrinth.com/user/bl4ckscor3)|MIT|
|[Skyboxify](https://modrinth.com/mod/skyboxify)|[lowercasebtw](https://modrinth.com/user/lowercasebtw)|GPL-3.0-only|
|[Sodium](https://modrinth.com/mod/sodium)|[douira](https://modrinth.com/user/douira), [IMS](https://modrinth.com/user/IMS), [jellysquid3](https://modrinth.com/user/jellysquid3)|LicenseRef-Polyform-Shield-1.0.0|
|[Sodium Extra](https://modrinth.com/mod/sodium-extra)|[FlashyReese](https://modrinth.com/user/FlashyReese)|LGPL-3.0-only|
|[Sodium Shadowy Path Blocks (SSPB)](https://modrinth.com/mod/sodium-shadowy-path-blocks)|[Rynnavinx](https://modrinth.com/user/Rynnavinx)|LGPL-3.0-only|
|[StackDeobfuscator](https://modrinth.com/mod/stackdeobf)|[booky10](https://modrinth.com/user/booky10)|LGPL-3.0-only|
|[SuperMartijn642's Config Lib](https://modrinth.com/mod/supermartijn642s-config-lib)|[SuperMartijn642](https://modrinth.com/user/SuperMartijn642)|LicenseRef-All-Rights-Reserved|
|[Tax Free Levels](https://modrinth.com/mod/tax-free-levels)|[Fourmisain](https://modrinth.com/user/Fourmisain)|MIT|
|[Terralith](https://modrinth.com/mod/terralith)|[Apollo](https://modrinth.com/user/Apollo), [catter1](https://modrinth.com/user/catter1), [Starmute](https://modrinth.com/user/Starmute)|LicenseRef-Stardust-Labs-License|
|[Text Placeholder API](https://modrinth.com/mod/placeholder-api)|[Patbox](https://modrinth.com/user/Patbox)|LGPL-3.0-only|
|[TooltipToggles](https://modrinth.com/mod/tooltiptoggles)|[yungando](https://modrinth.com/user/yungando)|CC0-1.0|
|[Trading Post](https://modrinth.com/mod/trading-post)|[Fuzs](https://modrinth.com/user/Fuzs), [LunaPixelStudios](https://modrinth.com/user/LunaPixelStudios)|MPL-2.0|
|[TrashSlot](https://modrinth.com/mod/trashslot)|[BlayTheNinth](https://modrinth.com/user/BlayTheNinth)|LicenseRef-All-Rights-Reserved|
|[Traveler's Backpack](https://modrinth.com/mod/travelersbackpack)|[Tiviacz1337](https://modrinth.com/user/Tiviacz1337)|LGPL-3.0-only|
|[Universal Enchants](https://modrinth.com/mod/universal-enchants)|[Fuzs](https://modrinth.com/user/Fuzs), [LunaPixelStudios](https://modrinth.com/user/LunaPixelStudios)|MPL-2.0|
|[Village Healthcare](https://modrinth.com/mod/village-healthcare)|[HyperPigeon](https://modrinth.com/user/HyperPigeon)|MIT|
|[Waystones](https://modrinth.com/mod/waystones)|[BlayTheNinth](https://modrinth.com/user/BlayTheNinth)|LicenseRef-All-Rights-Reserved|
|[Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap)|[thexaero](https://modrinth.com/user/thexaero)|LicenseRef-All-Rights-Reserved|
|[Xaero's World Map](https://modrinth.com/mod/xaeros-world-map)|[thexaero](https://modrinth.com/user/thexaero)|LicenseRef-All-Rights-Reserved|
|[YetAnotherConfigLib (YACL)](https://modrinth.com/mod/yacl)|[isxander](https://modrinth.com/user/isxander)|LGPL-3.0-or-later|
|[Your Options Shall Be Respected (YOSBR)](https://modrinth.com/mod/yosbr)|[shedaniel](https://modrinth.com/user/shedaniel)|LGPL-3.0-only|
|[Zoomify (Zoom)](https://modrinth.com/mod/zoomify)|[isxander](https://modrinth.com/user/isxander)|LGPL-3.0-only|

## Resource Packs

| Name | Author | License |
| --- | --- | --- |
|[Spectral](https://modrinth.com/resourcepack/spectral)|[Fulmine](https://modrinth.com/user/Fulmine)|CC-BY-NC-SA-4.0|

*All relevant information is sourced from [Modrinth](https://modrinth.com/).*

*The vast majority of this list was generated using [justin-carver/sculkr](https://github.com/justin-carver/sculkr). Thanks to its author Justin Carver and contributors.*

## FAQ

Q: The game crashes / throws errors on startup. What do I do?
A: Please check logs/latest.log first, and search the Issues to see if the same problem has already been reported. If not, open a new Issue with the log attached, and I'll do my best to look into it.

Q: Can I add my own mods?
A: Yes, but it may cause compatibility issues.

Q: How do I update the modpack?
A: Download the new archive and import it in your launcher (possibly under "Update Modpack"), overwriting the old version. Make sure to back up your saves.

## License

This modpack is licensed under [BSD 3-Clause](LICENSE). The Elixir-related mod selection, configuration files, resource packs, and other content provided by Elixir are copyright of their original author Firebolt360, under their original [BSD-3-Clause](LICENSE-Elixir).

Third-party mods included in this modpack follow the licenses of their respective original authors. See each mod's `.pw.toml` file and the mod's source page for details.

*Note: Modrinth only provides a BSD-3-Clause template and does not include Elixir's specific information such as the year. The `LICENSE-Elixir` in this repository was completed based on that template and the Elixir author's information, and is for reference only. If it differs from Elixir's official information, please refer to the official page or documentation.*

## Star Support

If this modpack has been helpful to you, feel free to give it a Star ⭐!
