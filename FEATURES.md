# Pack de Texturas HD y mejoras — by The128ReBits

SWROTS-PC v0.5.0 de jedijosh920 · rev20261026d · ES/EN.

**Five text languages are retained:** play with text in **Spanish, English, French, German and Italian**. Voices remain in English. Some parts of the installer and importer are still in Spanish.

**Se mantiene el multilenguaje:** puedes jugar con textos en **español, inglés, francés, alemán e italiano**. Las voces siguen en inglés. Algunas partes del instalador y del importador todavía están en español.

## Español — funciones y cambios por revisión

### Funciones del pack, no novedades de rev d

- 2.338 DDS de The128ReBits, en un conjunto de 2.339 archivos HD y 2.639.637.281 bytes. Resolución original del pack conservada, sin reducir ni regenerar las texturas.
- Instalador para añadir el pack a un juego existente o preparar una instalación nueva con el port y los datos del disco propio; configurador para sus opciones.
- Textos del pack en ES/EN/FR/DE/IT, con partes de instalación e importación aún en español. Voces en inglés; no hay doblaje nuevo.
- 40 fichas y ajustes de personajes; Palpatine con sable o bláster, también como J2.
- Selección de arma automática, sable, bláster o nativa; selección de personaje y opciones J1/J2 con mando.
- Modos Fiel y Locura y ajustes del cooperativo. El cooperativo original es del port.
- Integración gráfica opcional con DLSS y componentes de terceros.
- Importador del Jedi Modpack v1.0 con selección individual de diez módulos. El modpack se obtiene aparte desde su autor y no se incluye.

La adaptación toma como base **v0.5.0 de jedijosh920**. HvV hasta 5v5 y Battlefront proceden de ese port y están incluidos en la adaptación. No son modos creados por The128ReBits ni novedades propias de rev d.

**Cambio de personaje en campaña:** los 40 personajes que ya tenía el pack se pueden cambiar en plena partida desde mi selector del menú de pausa, incorporado en la edición para v0.4.0. Los personajes extra del Jedi Modpack y los dos nuevos de JediJosh —Comandante Cody y Droid Commander— también pueden jugarse en campaña, pero elegirlos en ese selector reinicia el nivel actual para aplicar el cambio.

### rev d — novedad de esta revisión

- Selección de mods opcionales durante **Instalación nueva** y al actualizar un juego existente, inicialmente desmarcados.
- Acceso a la página del autor y a su descarga; el usuario obtiene el ZIP en el navegador y lo selecciona localmente.
- Revisión individual de los módulos y guardado de la selección.
- Instalación del juego y del pack base primero; aplicación posterior de los módulos elegidos.
- Comprobaciones de hashes, rutas y colisiones antes de copiar. Un archivo diferente no se sobrescribe automáticamente.
- Si falla un opcional, se conserva la base instalada y se explica el motivo. Base instalada no certifica funcionamiento en partida.
- El importador también se puede abrir al terminar.

### Demostrado

Pruebas en partida realizadas por The128ReBits, incluida la campaña y las cinemáticas. Los recuentos siguientes corresponden a comprobaciones técnicas automatizadas independientes:

Pruebas técnicas sin ejecutar el juego: **36 PASS** del flujo de opcionales y **31 PASS** del importador con un juego falso y los datos conocidos del ZIP. Créditos: **10 PASS**; manifiesto de **2.431 filas y 7 artefactos**, sin discrepancias; **2.439 archivos** comprobados mediante SHA256SUMS y ZIP de **2.440 entradas** con CRC y hashes verificados. Regresión de enlaces/DLSS: PASS y un SKIP del enlace simbólico. Ajustes, controles y partidas conservados en los casos de prueba; originales a/b/c y juego real preservados por hash. Fuentes completas y evidencias preparadas por separado bajo sus licencias.

### Corregido

**rev b:** corregida la causa reproducida de `DLSS_REPARSE_POINT` al existir un junction por encima de la carpeta del juego. Se distinguen los enlaces que redirigen de otros atributos de Windows y se mantienen las protecciones contra escapes de rutas y enlaces peligrosos dentro del destino. Se añadieron comprobaciones de reversión y diarios. Si falla el DLSS opcional, la base puede terminar con «Instalación terminada sin DLSS» y su motivo. No es una solución universal a DLSS.

**rev c:** retirada, en cinco idiomas, de las frases de `Credits.cs` que atribuían soporte PAL a esta revisión; actualización de los cinco archivos de créditos instalados; recompilación del instalador y configurador. Cinco PASS por EXE. No se han eliminado todas las menciones PAL de la aplicación.

### Pendiente

- Los cierres de Hoth y los errores C0000005 siguen abiertos.
- Instalación real completa con mods descargados por el usuario, DLSS de extremo a extremo y revisión de ventanas reales.
- Enlace simbólico sin probar; restaurar puede dejar carpetas vacías.
- Restaurar la base no desinstala los módulos opcionales, que mantienen su diario propio.
- Licencias de redistribución de `dlss_base` por confirmar; partes del flujo siguen en español y quedan menciones PAL en textos heredados.

**Alcance:** solo disco Xbox USA (NTSC-U), XBE MD5 `6460ef37862de3af364a0563a0a18c4e`; PAL y discos desconocidos rechazados antes de instalar. Una base común acota el mantenimiento y las pruebas; no prueba incompatibilidad de PAL ni resuelve por sí sola los cierres. No se promete edición PAL futura. No se incluyen juego, ISO, XBE, GameData ni Jedi Modpack.

**Autoría:** port de jedijosh920; todas las texturas HD y dirección creativa del pack de The128ReBits. Claude y Codex asistieron técnicamente bajo su dirección y revisión, sin asignarles cambios concretos no documentados. Gracias a Cxbx-Reloaded, Dear ImGui y los autores de los componentes gráficos y mods externos, que conservan sus créditos y licencias. Modificación independiente, sin carácter ni colaboración oficiales.

---

## English — features and changes by revision

### Pack features, not new in rev d

- 2,338 DDS textures by The128ReBits within a set of 2,339 HD files totalling 2,639,637,281 bytes. The original pack’s resolution is preserved without downscaling or regenerating textures.
- Installer for adding the pack to an existing game or preparing a fresh installation with the port and data from your own disc; a configurator for its options.
- Pack text in ES/EN/FR/DE/IT, with parts of installation and importing still in Spanish. English voices; no new dub.
- 40 character entries and settings; saber or blaster Palpatine, including P2.
- Automatic, Saber, Blaster or Native weapon selection; controller character selection and P1/P2 options.
- Faithful and Madness modes and co-op settings. The original co-op belongs to the port.
- Optional graphics integration with DLSS and third-party components.
- Jedi Modpack v1.0 importer with individual selection of ten modules. Obtain the modpack separately from its author; it is not bundled.

The adaptation uses **jedijosh920’s v0.5.0** as its base. HvV up to 5v5 and Battlefront come from that port and are included in the adaptation. They are not modes created by The128ReBits or additions specific to rev d.

**Campaign character switching:** the pack’s existing 40 characters can be switched during gameplay through my pause-menu selector, introduced in the pack for v0.4.0. The extra Jedi Modpack characters and JediJosh’s two new characters —Commander Cody and Droid Commander— can also be used in the campaign, but choosing them in that selector restarts the current level to apply the change.

### Rev d — new in this revision

- Optional mod selection during both **fresh installation** and updating an existing game; all options start unchecked.
- Access to the author’s page and download; the user downloads the ZIP in their browser and selects it locally.
- Individual module review and saved selection.
- Game and base pack installation first; selected modules applied afterwards.
- Hash, path and collision checks before copying. A differing file is not automatically overwritten.
- If an optional module fails, the installed base is retained and the reason is explained. Base installed does not certify in-game functionality.
- The importer can also be opened at the end.

### Demonstrated

Gameplay tests performed by The128ReBits, including the campaign and cutscenes. The following counts describe separate automated technical checks:

Technical tests without running the game: **36 PASS** for the optional mods flow and **31 PASS** for the importer using a fake game and the ZIP’s known data. Credits: **10 PASS**; a manifest of **2,431 rows and 7 artifacts**, with no discrepancies; **2,439 files** checked through SHA256SUMS and a **2,440-entry ZIP** with CRC and hashes verified. Link/DLSS regression: PASS and one symbolic-link SKIP. Settings, controls and saves preserved in the test cases; original a/b/c revisions and the real game preserved by hash. Complete sources and evidence prepared separately under their licenses.

### Fixed

**Rev b:** fixed the reproduced cause of `DLSS_REPARSE_POINT` involving a junction above the game directory. Redirecting links are distinguished from other Windows attributes, while protections against path escapes and dangerous links inside the destination remain. Rollback checks and journals were added. If optional DLSS fails, the base can finish with “Instalación terminada sin DLSS” (“Installation completed without DLSS”) and the reason. This is not a universal DLSS fix.

**Rev c:** statements claiming PAL support for this revision removed from `Credits.cs` in five languages; five installed credits files updated; installer and configurator rebuilt. Five PASS per EXE. PAL references have not been removed from the entire application.

### Pending

- Hoth crashes and C0000005 errors remain open.
- Full real installation with user-downloaded mods, end-to-end DLSS and inspection of actual windows.
- Symbolic-link testing pending; restoring may leave empty folders.
- Base restoration does not uninstall optional modules, which keep their own journal.
- `dlss_base` redistribution licenses remain to be confirmed; parts of the flow remain in Spanish and PAL references remain in inherited text.

**Scope:** Xbox USA (NTSC-U) disc only, XBE MD5 `6460ef37862de3af364a0563a0a18c4e`; PAL and unknown discs rejected before installation. One shared base keeps maintenance and testing manageable; it does not prove PAL incompatibility or resolve crashes by itself. No future PAL edition is promised. Game, ISO, XBE, GameData and Jedi Modpack are not included.

**Authorship:** port by jedijosh920; all HD textures and the pack’s creative direction by The128ReBits. Claude and Codex provided technical assistance under his direction and review, without assigning undocumented specific changes to either. Thanks to Cxbx-Reloaded, Dear ImGui, and the graphics component and external mod authors, who retain their credits and licenses. Independent modification, with no official status or official collaboration.


<details>
<summary>Historical v0.4.0 feature catalogue / Catálogo histórico v0.4.0</summary>

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


</details>
