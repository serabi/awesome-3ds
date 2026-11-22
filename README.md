# Awesome 3DS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Homebrew games, apps and tools for Nintendo 3DS consoles running custom firmware.

## Contents

- [Getting Started](#getting-started)
- [Custom Firmware](#custom-firmware)
- [Game Ports](#game-ports)
  - [Console Classics](#console-classics)
  - [PC and Indie Games](#pc-and-indie-games)
  - [Shooters](#shooters)
  - [Fan Games and Demakes](#fan-games-and-demakes)
- [Mods and Patches](#mods-and-patches)
- [Apps](#apps)
- [Save Management](#save-management)
- [Customization](#customization)
- [Emulators](#emulators)
- [Online Services](#online-services)
- [Development](#development)
- [Community](#community)
- [AI Disclosure](#ai-disclosure)

## Getting Started

- [3DS Hacks Guide](https://3ds.hacks.guide) - Step-by-step guide from a stock console to custom firmware.
- [Universal-DB](https://db.universal-team.net) - Searchable database of 3DS and DS homebrew.
- [Universal-Updater](https://github.com/Universal-Team/Universal-Updater) - On-console store that installs and updates homebrew from Universal-DB.
- [Forge Store](https://github.com/EstebanPdN/forge.store) - On-console store for community homebrew that includes access to EstebanPdN's various 3DS game ports.

## Custom Firmware

- [Luma3DS](https://github.com/LumaTeam/Luma3DS) - The standard custom firmware, with the Rosalina overlay menu and a plugin loader.
- [boot9strap](https://github.com/SciresM/boot9strap) - Boot-time code execution that loads Luma3DS.
- [GodMode9](https://github.com/d0k3/GodMode9) - Full-access file browser for NAND backups, dumping and system file management.
- [Homebrew Launcher](https://github.com/devkitPro/3ds-hbmenu) - Menu for launching `.3dsx` homebrew.
- [FBI-NH](https://github.com/nh-server/FBI-NH) - Title manager for installing and removing CIA files.
- [3dsDL](https://github.com/ankushKun/3dsDL) - Downloads files to the console from a URL or QR code.
- [TWiLight Menu++](https://github.com/DS-Homebrew/TWiLightMenu) - DSi-style menu for launching DS games and homebrew.
- [nds-bootstrap](https://github.com/DS-Homebrew/nds-bootstrap) - Boots DS games from the SD card.
- [open_agb_firm](https://github.com/profi200/open_agb_firm) - Runs GBA games on the console's built-in GBA hardware.

## Game Ports

### Console Classics

Native ports built from decompilation and recompilation projects.

- [Emerald 3DS](https://github.com/ZallaxDev/emerald-3ds) - Pokemon Emerald rebuilt as a fully 3D world with stereoscopic 3D and seven languages.
- [The Minish Cap 3DS](https://github.com/EstebanPdN/zelda-tmc-3ds) - The Legend of Zelda: The Minish Cap with dual-screen play.
- [A Link to the Past 3DS](https://github.com/EstebanPdN/zelda-alttp-3ds) - The Legend of Zelda: A Link to the Past, based on zelda3.
- [Ocarina of Time 3DS](https://github.com/Andresac90/OOT-64-3DS-Port) - The N64 version of Ocarina of Time, built from source.
- [soh-3ds](https://github.com/999sian/soh-3ds) - Experimental Ship of Harkinian port of Ocarina of Time.
- [Super Mario 64 3DS](https://github.com/sm64-port/sm64_3ds) - The original Super Mario 64 port.
- [Super Mario 64 3DS Port Ultimate](https://github.com/Epic0522/Super-Mario-64-3ds-port---Ultimate) - Super Mario 64 with extra effects and performance tuning.
- [SM64DS Enhanced](https://github.com/ethanseagull/sm64ds-enhanced) - Super Mario 64 DS rebuilt natively with enhancements.
- [Mario Kart 64 3DS](https://github.com/EstebanPdN/mario-kart-64-3ds) - Mario Kart 64 with settings for both Old and New 3DS.
- [Mario Kart Wii DS](https://github.com/ethanseagull/MarioKartWiiDS) - Mario Kart Wii converted from your own disc.
- [Star Haven](https://github.com/SecondaryLifer/StarHaven) - Paper Mario (N64), with save import from cartridge and emulators.
- [Super Mario Sunshine 3DS](https://github.com/ikevik/sms-3ds) - Work-in-progress port of Super Mario Sunshine.
- [Starwing 3DS](https://github.com/EstebanPdN/starwing-3ds) - Star Fox (SNES), based on Starfox Enhanced.
- [Super Metroid 3DS](https://github.com/CharlesAverill/sm-3ds) - Native port of Super Metroid.
- [G-Diffuser 3DS](https://github.com/cruxxxxxx/gdx-3ds) - F-Zero X, with an experimental Expansion Kit build.
- [Pokemon Snap 3DS](https://github.com/xXDankeyKongXx/psnap-3ds) - Pokemon Snap via N64Recomp.
- [Twin Embers](https://github.com/alex61194/twin-embers) - Pokemon FireRed, source only.
- [Pokemon Platinum 3DS](https://github.com/GabeSud0/pokeplatinum-3ds) - Pokemon Platinum with widescreen, stereoscopic 3D and a touch UI.
- [Kohjoh](https://github.com/estyseesghosts/kohjoh) - Pokemon HeartGold and SoulSilver.
- [FF9 3DS](https://github.com/maurizi/ff9-3ds) - Final Fantasy IX (PS1), built from the ff9-decomp project.
- [Sonic Mania 3DS](https://github.com/SaturnSH2x2/RSDKv5-Decompilation) - Sonic Mania on the RSDKv5 decompilation (New 3DS only).
- [Sonic CD 3DS Redux](https://github.com/Voxel9/Sonic-CD-11-3DS-Redux) - Sonic CD (2011) on its decompilation.
- [Sonic 1 and 2 3DS](https://github.com/JeffRuLz/Sonic-1-2-2013-Decompilation) - Sonic 1 and 2 (2013) on their decompilation (New 3DS only).

### PC and Indie Games

- [SV3DS](https://github.com/gonzalo-araoz/SV3DS-releases) - Stardew Valley 1.6, converted on the console from your Steam or GOG files.
- [HK3DS](https://github.com/silviognotti/HK3DS) - Hollow Knight with the whole map, all bosses and an HD build for the New 3DS.
- [Cinnamon](https://github.com/Project-Sunshine-Native/cinnamon) - GameMaker runner that plays Deltarune and other GameMaker games.
- [Needy Girl Overdose 3DS](https://github.com/Mirezepam/needy-girl-overdose-3ds-rom) - Needy Girl Overdose with dual-screen play.
- [DevilutionX](https://github.com/diasurgical/DevilutionX) - Diablo and Hellfire.
- [LEGO Island](https://github.com/isledecomp/isle-portable) - The 1997 game, built from its decompilation.
- [REGTA](https://github.com/Epic0522/REGTA-3DSPort-Complete) - GTA III, Vice City and Liberty City Stories (New 3DS only).
- [OpenRCT2 3DS](https://github.com/UhtredOfBamburg/OpenRCT2-3DS) - RollerCoaster Tycoon 2 with a dual-screen layout.
- [3D Pinball Space Cadet](https://github.com/MaikelChan/SpaceCadetPinball/tree/3ds) - The Windows pinball table.
- [Celeste Classic](https://github.com/lemon32767/ccleste) - C port of the original PICO-8 Celeste.
- [DDLC-LOVE](https://github.com/LukeZGD/DDLC-LOVE) - Doki Doki Literature Club rewritten in Lua.
- [Pixel Dungeon 3DS](https://github.com/deathbygin/pixeldungeon-3ds) - The roguelike Pixel Dungeon.
- [SCP Containment Breach 3DS](https://github.com/RedHairHobitGoblin/scpcb3ds) - Unofficial port of SCP - Containment Breach.
- [Bugdom](https://github.com/carrotcreamsoup/Bugdom) - Pangea Software's 3D platformer.
- [Cro-Mag Rally](https://github.com/carrotcreamsoup/CroMagRally) - Pangea Software's kart racer.
- [Raptor](https://github.com/RetroGamer02/raptor-consoles) - Call of the Shadows, rebuilt from reverse-engineered source.

### Shooters

- [Xash3DS](https://github.com/masterfeizz/Xash3DS) - Half-Life on the Xash3D engine.
- [ctrQuake](https://github.com/masterfeizz/ctrQuake) - Quake, with the shareware episode included.
- [Quake2CTR](https://github.com/masterfeizz/Quake2CTR) - Quake II.
- [ioQuake3DS](https://github.com/masterfeizz/ioQuake3DS) - Quake III Arena on ioquake3.
- [PrBoom+ 3DS](https://github.com/Voxel9/PrBoom-Plus-3DS) - Doom source port.
- [ctrHexenII](https://github.com/Rinnegatamante/ctrHexenII) - Hexen II.
- [DXX 3DS](https://github.com/iNdioNicarao/dxx-3ds) - Descent with hardware rendering and stereoscopic 3D (New 3DS only).
- [Postal 1 3DS](https://github.com/Taifuoguru/Postal-1-3DS) - Work-in-progress port of Postal.
- [Nazi Zombies: Portable](https://github.com/nzp-team/nzportable) - Call of Duty: Zombies demake on Quake engines.

### Fan Games and Demakes

- [Balatro3DS](https://github.com/idkhan/Balatro3DS) - Balatro remake with Steamodded-style mod support.
- [Geometry Dash 3DS](https://github.com/AleFunky/gd3ds) - Geometry Dash, including custom levels.
- [Papa's Pizzeria 3DS](https://github.com/zylonity/PapasPizzeria-n3DS) - Flipline Studios' pizza restaurant game.
- [Doors 3DS](https://github.com/Doors-3ds-Development-Team/Doors-3DS) - Demake of the Roblox horror game Doors.
- [Funkin3D](https://github.com/GuglioIsStupid/Funkin3D) - Friday Night Funkin' demake.
- [TheXTech](https://github.com/TheXTech/TheXTech) - Super Mario Bros. X engine rewritten in C++.
- [Super Haxagon](https://github.com/RedTopper/Super-Haxagon) - Super Hexagon clone.
- [Sonic Robo Blast 2](https://github.com/derrekr/srb2_3ds) - 3D Sonic fan game (New 3DS only).
- [ClassiCube](https://github.com/ClassiCube/ClassiCube) - Minecraft Classic client written from scratch in C.
- [Craftus Reloaded](https://github.com/RSDuck/craftus_reloaded) - Minecraft-style voxel sandbox.

## Mods and Patches

- [CTGP-7](https://ctgp-7.github.io) - Mario Kart 7 modpack with new tracks, characters and online play.
- [Minecraft Old 3DS Patcher](https://github.com/s4ammy/3DSMinecraft) - Patches Minecraft: New Nintendo 3DS Edition to run on the Old 3DS.
- [Multi-Pokemon Framework](https://github.com/semaj14/Multi-PokemonFramework) - Plugin for the generation 6 and 7 Pokemon games.
- [pk3DS](https://github.com/kwsch/pk3DS) - Windows editor and randomizer for the generation 6 and 7 Pokemon games.

## Apps

- [Twitch3ds](https://github.com/wk0t/Twitch3ds) - Twitch client with hardware H.264 video and chat (New 3DS only).
- [TriCord](https://github.com/2b-zipper/TriCord) - Discord client.
- [FourthTube](https://github.com/erievs/FourthTube) - YouTube client, forked from ThirdTube.
- [Moonlight for New 3DS](https://github.com/zoeyjodon/moonlight-N3DS) - Streams games from a PC (New 3DS only).
- [3dJelly](https://github.com/8-bitStudio/3d-jelly) - Jellyfin client.
- [sound3ds](https://github.com/PeppiDev/sound3ds) - SoundCloud and local music player.
- [ctrmus](https://github.com/deltabeard/ctrmus) - Music player for common audio formats.
- [Video Player for 3DS](https://github.com/Core-2-Extreme/Video_player_for_3DS) - Plays MP4 and other video files.
- [3dslibris](https://github.com/RigleGit/3dslibris) - Ebook and manga reader.
- [TinyVNC](https://github.com/badda71/TinyVNC) - VNC viewer.
- [DSSH](https://github.com/Fishason/DSSH) - SSH client.
- [Scratch Everywhere!](https://github.com/ScratchEverywhere/ScratchEverywhere) - Runs Scratch projects.
- [ftpd](https://github.com/mtheall/ftpd) - FTP server for moving files over Wi-Fi.
- [ControlMole](https://github.com/skrimby1/controlmole-3ds) - Play time limiter with a Luma3DS plugin that pauses games at your daily limit or bedtime. A cute mole tracks your screentime and tells you to go to bed when needed.

## Save Management

- [Checkpoint](https://github.com/BernardoGiordano/Checkpoint) - Backs up and restores 3DS and DS saves.
- [PKSM](https://github.com/FlagBrew/PKSM) - Save manager and editor for Pokemon generations 1 to 8.
- [JKSM](https://github.com/J-D-K/JKSM) - Save manager with extdata support.
- [Cloudpoint](https://github.com/dwalker109/cloudpoint) - Cloud save sync.

## Customization

- [Anemone3DS](https://github.com/astronautlevel2/Anemone3DS) - Theme and boot splash manager.

## Emulators

### On the Console

- [RetroArch](https://github.com/libretro/RetroArch) - Frontend for libretro emulator cores.
- [mGBA](https://github.com/mgba-emu/mgba) - Game Boy Advance emulator.
- [Snes9x for 3DS](https://github.com/matbo87/snes9x_3ds) - SNES emulator, maintained fork.
- [Red Viper](https://github.com/skyfloogle/red-viper) - Virtual Boy emulator that uses the 3D screen.
- [DaedalusX64 3DS](https://github.com/masterfeizz/DaedalusX64-3DS) - Nintendo 64 emulator.
- [ScummVM](https://github.com/scummvm/scummvm) - Engine for classic point-and-click adventure games.
- [DOSBox 3DS](https://github.com/MrHuu/dosbox-3ds) - DOS emulator.

### On Other Platforms

- [Azahar](https://github.com/azahar-emu/azahar) - 3DS emulator based on Citra.
- [Panda3DS](https://github.com/wheremyfoodat/Panda3DS) - High-level 3DS emulator.

## Online Services

- [Nimbus](https://github.com/PretendoNetwork/nimbus) - Connects the console to Pretendo Network, a replacement for Nintendo Network.

## Development

- [libctru](https://github.com/devkitPro/libctru) - Core library for 3DS homebrew.
- [citro3d](https://github.com/devkitPro/citro3d) - Wrapper for the PICA200 GPU.
- [citro2d](https://github.com/devkitPro/citro2d) - 2D drawing on top of citro3d.
- [picaGL](https://github.com/masterfeizz/picaGL) - OpenGL implementation used by many ports.
- [LovePotion](https://github.com/lovebrew/lovepotion) - LÖVE game framework for Nintendo homebrew.

## Community

- [r/3dshacks](https://www.reddit.com/r/3dshacks/) - Subreddit for 3DS homebrew and custom firmware.
- [GBAtemp](https://gbatemp.net) - Forum with release threads for most 3DS homebrew.
- [Universal-DB on GitHub](https://github.com/Universal-Team/db) - Where homebrew gets submitted to Universal-DB.

## AI Disclosure

This list was researched, curated and edited by a human, with help from AI tools. I also use AI tools and automations to help keep it up to date. I haven't run every project here, but I've tried a good portion of them.

I'm not affiliated with any of these projects. I do run [Just One More Catch!](https://justonemorecatch.app), a tracker for retro Pokémon playthroughs from Game Boy to 3DS ([source on GitHub](https://github.com/Interactive-Buffoonery/just-one-more-catch)).

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md), then open a pull request, or [suggest a project](https://github.com/serabi/awesome-3ds/issues/new?template=suggest-a-project.yml) if you'd rather not edit the list yourself.
