# HD Texture Pack & Improvements for JediJosh’s PC Port

**Revenge of the Sith · by The128ReBits**

[Cambios y documentación en español](CAMBIOS_ES.txt) · [README español](README_ES.md)

This catalogue documents the pack’s additions from the installer/configurator credits, final changelog and source materials. The native PC port and its original features are credited separately below.

## HD textures and visual identity

- 2,338 adapted HD DDS textures at the original resolution of The128ReBits’ pack, with activation/deactivation from the configurator.
- Regional resource matching for recognised PAL and USA discs; 2,908 checked variants are resource variants, not a claim of 2,908 HD textures.
- 17 supplementary STX resources. The original disc loading illustrations are retained. Coverage is partial and texture resolutions vary.

## PAL / USA regional support

- A dedicated PAL core alongside the USA core, with verified regional addresses and automatic regional selection for recognised disc data.
- Installation from the player’s own supported Xbox ISO/XISO or an existing compatible installation. This does not promise every revision, NTSC-J or future port compatibility.

## Five text languages — an addition over the English-language v0.4.0 base

- Spanish, English, French, German and Italian menus, subtitles and general game text, using the supported game data.
- Character entries, control notes, installer, configurator, credits and player documentation in the same five languages.
- Voices remain in English. This adds no Spanish dub or new voice acting.

## Character entries and playable adaptations

- 40 entries covering characters, classes and variants, with named outfits, functionality ratings, notes and recommended weapons.
- Ratings distinguish Complete, Native actions, Experimental, Partial and Explore. These are not 40 new original character models or a guarantee that every character can finish every mission.
- Palpatine is one adaptation within the pack: compatible combat controllers for saber/blaster play, including P2, instead of the cinematic controller that previously failed.
- The story-only Grievous entry is excluded. External portrait BMPs are removed from this distribution; disc-resource fallback remains where available.

## Weapon profiles for each character

- Automatic, Saber, Blaster and Native selection, with a recommended weapon and per-character combat style and damage settings.
- Automatic recommendations follow the character/class; compatible manual choices and personal profiles can override them.
- The weapon selector is available in the game’s selector and in the configurator. Original models, resources and animations retain their authorship.

## Controller character selection inside the game

- Open and operate the character selector from the pause menu using a controller, for P1 and P2. B/Circle returns to pause; choices apply when returning to play.
- P2 selection is deferred until pause ends, so menu input is not consumed by combat actions.
- A per-level cache reuses up to 16 distinct character/body combinations, addressing the previous restart after two changes. This is a finite cache, not unlimited character loading.

## Revised native actions by class

- Super battle droid: revised native melee variants, sustained fire and charge.
- Buzz droid: saw, jump/grab, rolling and rebound actions; targeted protection against its lethal self-damage routes.
- Flying battle droid: alternating blasters, arm blade/shield and thruster effects.
- Walker: cannon and native charge integration. Its aiming and charge behaviour remain limited.
- Flamethrower: fire, aerial dodge and native grab. Grab damage remains a known pending issue.
- Droideka: firing, shield integration and corrected death handling. The visible shield bubble remains a known pending issue.
- B1 and clones: firing and shove; held B1 fire no longer overrides its shove.
- Grapple droid: native hook with a wait between uses.
- R2-D2: probe, celebration and repair actions; celebration is cosmetic.
- C-3PO: repair and nearby-partner healing with a cooldown. Entries describe capabilities and restrictions.

## Gameplay modes, balance and mission help

- Faithful mode for a first playthrough or revisiting the original adventure; Madness for experimenting with the character roster.
- Per-character Madness challenges and finite health/damage/defence settings, using the mission protagonist as the baseline for balance.
- Documented balance additions include buzz droid health ×2 / half incoming damage / damage ×1.5, R2 health ×1.25 / damage ×1.5, and walker damage ×2.25 when the relevant settings apply.
- Mission help temporarily returns P1 to the expected protagonist for mandatory story events, with an option to return to the chosen character. This is not a universal quick-save or save-state system.

## Co-op additions over JediJosh’s original co-op

- Character selection and separate profiles for P1/P2, including P2 character/weapon preferences.
- Balanced health and P2 shield additions, with control and configuration options in the selector/configurator.
- The underlying two-player story/bonus co-op and shared camera are JediJosh’s work. This package does not add online play or split screen.

## Character and menu fixes

- Restored the installation of additional controls for eight affected classes after a previous hook regression.
- Revised B1 fire/shove interaction; combat actions respect pause; R2 hook/control cleanup on reload; flamethrower timings/native grab restored; droideka death handling corrected.
- Addressed the trapped Madness menu and the former restart threshold when repeatedly changing characters, with input handling and per-level caching. See the changelog and each entry for remaining limitations.

## The128ReBits’ separate configurator

- One window for graphics, HD, modes, language, characters, weapon profiles and co-op/P2 options; scrolling supports smaller screens.
- Quick presets, display mode, widescreen, VSync, internal resolution, anisotropic filtering, MSAA, bloom and HD toggle; optional graphics management.
- 30, 60, 120, 165, 180 and 240 FPS choices. 30 FPS is recommended for story play; every higher setting is experimental. The menu value is not a measured performance claim.
- Graphics configuration opens in its own window. The character selector is inside the pause menu.

## Keyboard and mouse editor

- Editable actions with multiple bindings, mouse side buttons and duplicate-binding warnings.
- Mouse-as-right-stick options, sensitivity and walk speed.
- Saving preserves unknown configuration keys and the existing encoding/comments where supported, with a previous copy kept.

## Utilities and maintenance

- Named graphics/control profiles; save backups and restoration; installation checks; bug-report ZIP creation; folder shortcuts.
- Launch preferences, including closing the configurator or choosing high priority when launching; reset graphics/control preferences.
- Xbox ISO import and access to the installed-game configuration without reinstalling the pack. Review bug reports before sharing them.

## One installer, two paths

- Existing game: choose the working game folder and add the HD pack/improvements while preserving the original loader, game data, saves and settings, with backups of replaced files.
- Fresh installation: supply JediJosh’s v0.4.0 port ZIP/extracted folder, your supported PAL/USA Xbox ISO/XISO and a new or empty destination. HD is already included.
- Progress and approximate remaining time across preparation, ISO extraction, checks, copying and installation; manifest/hash and regional checks; installation record and backup.
- Installation checking, backup restoration and configurator access from the installer. Restoration refuses files changed by the user since installation.
- Warnings and backup before replacing another port version with this v0.4.0-based core. The installer does not automatically launch the game.

## Optional experimental DLSS 5 and easy management

- Optional experimental DLSS 5 community integration, with automatic downloads of missing components. Open Configurator → Installation and DLSS... → Install and enable DLSS, then restart the game. The installer can request it during setup too.
- Reuse local components, disable DLSS or customise its settings from the assistant. SHA-256 checks verify downloads, and the bridge can fall back to Direct3D 9 if loading fails. File checks do not certify active GPU processing.
- The chain uses components by dgVoodoo2, ReShade, DLSS5-Feeder, RenoDX, LumeniteFX, NVIDIA runtime authors and the Lecram community build. Their technologies are not developed by The128ReBits.
- Restricted TRAA and iMMERSE files are obtained from official pinned sources rather than redistributed in the ZIP. Optional graphics are not required for the HD textures.

## Documentation, sources and distribution

- Player documentation as plain TXT in five languages, complete credits, changes, installation help and file-location guides.
- Corresponding PAL/USA regional source snapshots, installer/configurator sources, build scripts, upstream notices and a source/binary hash map are supplied with the release and player archive.
- A kit for adapting the regional changes to later JediJosh releases is included as developer material; it is not a promise that later releases already work.
- The game, ISO, original port loader and NVIDIA runtime DLLs are not included in the player pack. The user provides their own supported game and original port.

## JediJosh’s original work — thank you

JediJosh created the native Windows port, including its graphics, sound, higher internal resolution, widescreen, keyboard/mouse and Xbox/PlayStation controller support. He added Yoda/Sith Yoda in Versus, the base character/class/costume/body tools, loading characters from other levels, spawning, duel moves, the original two-player story and bonus co-op, free camera, debug tools, loose-file modding and port fixes.

The128ReBits’ additions expand that foundation. Original characters, models, animations, sound and game resources retain their respective authors and owners. The original game is by The Collective and LucasArts. Community and third-party acknowledgements remain in the full credits and source notices.

## Verification and current limits

The author reported PAL/USA play tests in the project history. Distribution checks and installer/configurator builds were repeated for the reviewed package, including manifest/ZIP integrity and pinned-download checks. This packaging revision did not receive a new complete playthrough/GPU test, and the regional cores were not rebuilt during packaging. Portrait fallback presentation, higher FPS and the documented character limitations must not be described as universally verified.

Known character issues include the droideka bubble, flamethrower grab damage and walker aiming/charge. HD coverage is partial. Read the per-entry ratings and release guide.

[Original port by JediJosh](https://github.com/jedijosh920/SWROTS-PC) · [Full credits](CREDITS_EN.txt) · [Changes](CHANGES_EN.txt) · [Installation guide](GUIDE_EN.txt)
