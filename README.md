![Promotional illustration / Ilustración promocional](https://media.moddb.com/images/mods/1/74/73782/Sith_HD_Improvements_Final_EN.png)

# Pack de Texturas HD y mejoras — by The128ReBits

**Current update / Actualización actual: SWROTS-PC v0.5.0 · rev20261026d · Xbox USA / NTSC-U only**

**Five text languages are retained:** play with text in **Spanish, English, French, German and Italian**. Voices remain in English. Some parts of the installer and importer are still in Spanish.

**Se mantiene el multilenguaje:** puedes jugar con textos en **español, inglés, francés, alemán e italiano**. Las voces siguen en inglés. Algunas partes del instalador y del importador todavía están en español.

[Download player pack, corresponding sources and checksums / Descargar pack, fuentes y comprobantes](https://github.com/The128ReBits/HD-Pack-and-Improvements-for-JediJosh-PC-Port/releases/tag/hd-pack-swrots-v0.5.0-rev20261026d) · [Full update notes / Notas completas](UPDATE_v0.5.0.md)

## English — what changed

JediJosh’s new modes and characters made it worth adapting my pack just days after its release. His v0.5.0 adds Heroes vs Villains up to 5v5, Battlefront conquest, Commander Cody, Droid Commander, and custom characters/maps. Credit for those additions belongs to JediJosh. My work adapts my HD textures, gameplay improvements, selector, configurator and installer to his port.

- 2,338 HD DDS textures at their original pack resolutions; 40 character entries, weapon settings, P1/P2 selection and Faithful/Madness modes.
- **The pack’s existing 40 characters can be switched during gameplay through my pause-menu selector, introduced for v0.4.0.** The extra Jedi Modpack characters and JediJosh’s two new fighters can also be used in campaign, but selecting them restarts the current level.
- [Jedi Modpack v1.0](https://github.com/jedijosh920/SWROTS-PC/discussions/56) is a separate optional download from its author, with Darth Maul, Darth Revan, Revan, Luke Skywalker and five maps. It is not bundled.
- Rev d offers individual optional mod selection during both installation paths. The base installs first; selected modules follow.
- Five pack text languages, with parts of installation/importing still in Spanish. English voices. Optional DLSS integration; HD also works without it.

Extract the player ZIP and run **Instalar Pack HD y mejoras.exe**. Choose an existing game or a fresh installation using [JediJosh’s v0.5.0 port](https://github.com/jedijosh920/SWROTS-PC/releases/tag/v0.5.0) and data from your own Xbox USA disc. This revision accepts XBE MD5 `6460ef37862de3af364a0563a0a18c4e`; PAL and unknown discs are rejected. The game, ISO, XBE, GameData and Jedi Modpack are not included. Sources for this revision are in the separate **FUENTES_Y_EVIDENCIAS** release asset.

**Demonstrated:** gameplay tested by The128ReBits; separate technical checks recorded 36 PASS for optional installation, 31 for importing and 10 for credits. **Fixed:** reproduced DLSS_REPARSE_POINT cause (b), specific PAL credit claims (c); optional mod selection during installation added in d. **Pending:** Specific installer/DLSS/symlink checks and redistribution license confirmation for `dlss_base` remain pending. See the full notes for all limits.

## Español — novedades y descarga

Las novedades de JediJosh me animaron a adaptar mis mejoras a última hora, apenas unos días después de publicar el pack. **El mérito de HvV hasta 5v5, Battlefront, Cody, Droid Commander y los personajes y mapas personalizados es suyo.** Mi aportación es adaptar mis texturas HD, mejoras, selector, configurador e instalador a su port.

**Los 40 personajes que ya tenía el pack se pueden cambiar en plena partida desde mi selector de pausa, incorporado para v0.4.0.** Los personajes extra del Jedi Modpack y los dos nuevos de JediJosh también pueden utilizarse en campaña, pero elegirlos en el selector reinicia el nivel actual.

Descarga el ZIP del jugador, extrae todo y abre **Instalar Pack HD y mejoras.exe**. HD ya está incluido. Rev d permite elegir los módulos opcionales durante la instalación nueva o al añadir el pack a un juego existente; el Jedi Modpack se descarga aparte desde su autor. Esta revisión es **solo NTSC-U** para mantener una base común de desarrollo. No incluye juego, ISO, XBE, GameData ni Jedi Modpack. Los textos del pack están en cinco idiomas, con partes del instalador/importador aún en español; voces en inglés.

**Demostrado:** probado en partida por The128ReBits; 36/31/10 PASS técnicos por separado. **Corregido:** causa reproducida de DLSS_REPARSE_POINT (b) y créditos concretos PAL (c); d añade la selección de opcionales durante la instalación. **Pendiente:** Comprobaciones específicas del instalador/DLSS/symlink y confirmación de licencias de `dlss_base`; detalles en las notas completas.

All HD textures and creative direction / Todas las texturas HD y dirección creativa: **The128ReBits**. Port and original co-op / Port y cooperativo original: **jedijosh920**. Thanks / Gracias: Cxbx-Reloaded, Dear ImGui and the graphics component and external mod authors. Claude and Codex provided technical assistance under The128ReBits’ direction and review. Independent modification; no official collaboration / Modificación independiente, sin colaboración oficial.

[YouTube](https://www.youtube.com/@The128ReBits) · [Ko-fi](https://ko-fi.com/the128rebits) · [Patreon](https://www.patreon.com/The128ReBits) · [Support JediJosh / Apoyar a JediJosh](https://ko-fi.com/jedijosh920)


### Weapons and each character’s own actions

**Most compatible humanoids can use a blaster or lightsaber.** The selector offers Automatic, Saber, Blaster and Native, with individual character profiles and P1/P2 settings.

For droids and other special bodies, I revised controls and native attacks: the super battle droid’s wrist blaster, melee and charge; the buzz droid’s saw, leap/grab, rolling and rebound; the flying droid’s own firing and actions; the walker’s cannon and charge; droideka/B1/clone firing and class-specific actions; and grapple droid and flamethrower controls. R2-D2 has probe zap and repair, while C-3PO can repair itself and help a nearby partner, with a cooldown. Combat, balance and control work underpins the roster: check each class’s capabilities. Cody and Droid Commander retain JediJosh’s own kit.

### Armas y acciones propias de cada personaje

**La mayoría de los humanoides compatibles pueden usar bláster o sable láser.** El selector ofrece Automática, Sable, Bláster y Nativa, con perfiles y ajustes por personaje y para J1/J2.

Para los droides y otros cuerpos especiales he revisado controles y ataques nativos: bláster de muñeca, golpes y embestida del superdroide; sierra, salto/agarre, rodar y rebote del zumbador; disparos y acciones propias del droide volador; cañón y embestida del andador; disparos y acciones de droideka/B1/clones; y controles del droide de garra y del lanzallamas. R2-D2 dispone de sonda eléctrica y reparación, y C-3PO puede repararse y ayudar al compañero cercano, con recarga. Hay trabajo de combate, equilibrio y controles detrás de las fichas: consulta las capacidades de cada clase. Cody y Droid Commander conservan su kit de JediJosh.


<details>
<summary>Historical v0.4.0 documentation / Documentación histórica v0.4.0 (PAL/USA)</summary>

The following describes the earlier release only. / Lo siguiente describe únicamente la entrega anterior.

![Star Wars: Episode III — Revenge of the Sith. Promotional artwork for the HD pack and gameplay improvements.](https://media.moddb.com/images/mods/1/74/73782/Sith_HD_Improvements_Final_EN.png)

*Promotional illustration; the screenshots and explanatory images below show the actual project.*

# Star Wars: Episode III — Revenge of the Sith

## HD Textures & Gameplay Improvements for JediJosh’s PC Port

**Revenge of the Sith · by The128ReBits**

**Native Windows port by [JediJosh](https://github.com/jedijosh920/SWROTS-PC). HD texture pack and added improvements by The128ReBits.**

[Español aquí abajo](#español) · [Documentación completa en español](README_ES.md) · [Free download](../../releases/latest) · [Installation guide](GUIDE_EN.txt) · [Full credits](CREDITS_EN.txt) · [Complete feature catalogue](FEATURES.md)

Return to the Xbox game on PC with **2,338 HD textures, five text languages, revised playable characters, controller character selection from pause for P1/P2, expanded co-op options, optional experimental DLSS 5 with easy setup, and my own configurator and installer**.

![Feature overview — real port capture and explanatory labels](https://media.moddb.com/images/mods/1/74/73782/banner_articulo.png)

## What The128ReBits adds

| Area | Included in this pack |
|---|---|
| HD textures | 2,338 adapted DDS textures, toggleable, at the original resolution of my HD pack; partial coverage |
| **Multilingual game** | **Spanish, English, French, German and Italian subtitles, menus and game text**, alongside translated character entries, installer, configurator and credits. Added over the English-language v0.4.0 base. **Voices remain in English.** |
| PAL and USA | Separate regional cores and automatic selection for recognised Xbox discs |
| Characters | 40 rated entries covering characters, classes and variants; revised controls and native actions, notes, outfits and recommended weapons |
| Weapons | Automatic, Saber, Blaster or Native profiles, with per-character style and damage settings |
| In-game selection | Improved controller-friendly pause-menu selector, character cards and portraits, P1/P2 choices and per-level character cache |
| Gameplay | Faithful and Madness modes, per-character challenges, balanced health/damage/defence and mission help |
| Co-op additions | Character selection and profiles, balanced health and P2 shield, building on JediJosh’s existing two-player co-op |
| Configurator | Separate window for graphics, HD, modes, characters, weapons, P2 and language; keyboard/mouse editor, side buttons, multiple bindings and duplicate warnings |
| Optional DLSS 5 | Experimental community integration; automatic downloads, verified components, install/enable/disable controls and quality settings |
| Utilities | Named settings/control profiles, save backups/restoration, installation checks, bug reports, folder access and launch preferences |
| Installer | Add to a working port or prepare a fresh installation from your port ZIP/folder and own Xbox ISO; progress, regional checks and backups |

Revised native actions include the super battle droid, buzz droid, flyer, walker, flamethrower, droideka, B1/clones, grappler, R2-D2 and C-3PO. Palpatine is one of the playable adaptations, including P2. These are adaptations of the game’s own resources and actions. Functionality differs by entry; read its rating and notes.

## JediJosh made the foundation

JediJosh created **JediJosh’s PC port**, the native Windows port: graphics and sound, higher internal resolution, widescreen, keyboard/mouse and Xbox/PlayStation controllers. His work also adds Yoda and Sith Yoda in Versus, character/body selection and loading from other levels, duel moves, the original two-player story co-op, free camera, debug/modding tools, loose-file replacements and port fixes.

**Thank you, JediJosh, for bringing the game to PC and sharing your code, research and tools.** [Original project](https://github.com/jedijosh920/SWROTS-PC) · [Support JediJosh](https://ko-fi.com/jedijosh920)

## Download and install

Open [Releases](../../releases/latest) and download **Pack_Texturas_HD_y_mejoras_by_The128ReBits_PAL-USA_SWROTS-PC_v0.4.0.zip**. The automatic “Source code” archives are not the player installer.

You need **[JediJosh’s PC port v0.4.0](https://github.com/jedijosh920/SWROTS-PC/releases/tag/v0.4.0)**, your **own recognised PAL/USA Xbox game**, and Windows compatible with the port. The game, ISO and original port files are not included. The HD textures for this native PC-port edition are already included; I recommend leaving them enabled. No extra texture download is needed. My [separate PS2/PCSX2 pack](https://www.moddb.com/mods/star-wars-episode-iii-revenge-of-the-sith-hd-texture-pack-for-pcsx2/downloads/revenge-of-the-sith-hd-texture-pack-pcsx2-pal-usa-region-guide) is for the emulated PS2 game and uses its own installation.

Download the ZIP and extract all its contents into a folder on your PC. Open that folder and run **Instalar Pack HD y mejoras.exe**. You can select English in the installer’s language menu.

1. **Already working:** choose the first option and select your installed game folder. The installer backs up replaced files and preserves your executable, game data, saves and settings.
2. **Fresh installation:** choose the second option, provide JediJosh’s v0.4.0 port ZIP/extracted folder and your supported Xbox ISO/XISO, then choose a new or empty destination. HD is included.

Open the configurator afterwards to choose language, mode and preferences. The installer does not automatically start the game. Optional third-party graphics downloads are managed by the assistant; DLSS is not required for HD.

## Optional DLSS 5: easy setup

Open **Configurator → Installation and DLSS...**, leave automatic downloading enabled and press **Install and enable DLSS**. The assistant downloads missing components and checks their SHA-256 hashes. It can also reuse a complete local component folder. Restart the game afterwards. **High quality (77%)** is a starting point; you can customise or disable the integration from the same assistant.

You can request this optional download during the main installation too. The HD textures work independently of DLSS. This is an **experimental community integration**, using dgVoodoo2, ReShade, DLSS5-Feeder, RenoDX, LumeniteFX and NVIDIA runtimes, including the Lecram community build. The game integration, profile and setup tools are my work; the components retain their authorship. GPU results depend on the system, and file checks alone do not confirm active processing.

## Compatibility and known issues

**30 FPS is recommended for story play. Higher settings are experimental.** Support targets v0.4.0 and recognised PAL/USA revisions. Another port version may be replaced with the mod’s v0.4.0-based core after a warning and backup; later port features are not automatically retained.

HD coverage is partial and texture resolutions vary. The 40 entries are characters/classes/variants, with different functionality ratings. Known pending issues include the droideka bubble, flamethrower grab damage and walker charge/aiming. External portrait BMPs have been removed; disc-resource fallback is retained where available, and its presentation needs in-game review. Co-op uses JediJosh’s shared camera; no online mode is added.

## Source, checks and credits

The release includes a **corresponding-source ZIP**, regional PAL/USA source trees, installer/configurator source and build scripts. The player archive also includes the sources. [Binary/source map](SOURCE-MAP.json) · [Checksums](SHA256SUMS.txt) · [Changes](CHANGES_EN.txt) · [Licence map](LICENSE_MAP.md).

Base: upstream v0.4.0 commit `f459f126fd9a62065fa1764d7127469900a6e653`. Installer/configurator compilation, manifest/ZIP checks and pinned download integrity checks passed. This distribution revision has not received a new gameplay/GPU test; regional core rebuilds were not repeated during packaging. See the source map for the recorded build provenance.

Original game by **The Collective and LucasArts**. Original game resources and trademarks retain their respective owners. Port and modified code retain their GPL notices; third-party components retain their own terms. Optional graphics technologies are credited to their authors.

For bugs, use **Configurator → Utilities → Create bug report**, review it, and include region, mission, character and reproduction steps in [Issues](../../issues).

## Follow and support

The finished pack is **free**. Watch gameplay and updates on [YouTube](https://www.youtube.com/@The128ReBits). If you would like to support my work: [Ko-fi](https://ko-fi.com/the128rebits) · [Patreon](https://www.patreon.com/The128ReBits). Support is optional. [All links](https://linktr.ee/the128rebits).

---

## Español

**Port nativo de [JediJosh](https://github.com/jedijosh920/SWROTS-PC). Pack de Texturas HD y mejoras de The128ReBits.**

He adaptado mi pack HD al port de PC y trabajado en los personajes, sus controles y la configuración. Incluye **2.338 texturas HD**, soporte PAL/USA, cinco idiomas de texto y selección con mando desde la pausa para **J1 y J2**. Las voces permanecen en inglés.

Las 40 fichas reúnen personajes, clases y variantes con notas, valoraciones y armas recomendadas. Entre las revisiones hay ataques del superdroide, acciones y resistencia del zumbador, cañón del andador, reparación de R2-D2/C-3PO y controles para otras clases. **Fiel** permite revivir la aventura original; **Locura**, experimentar con el reparto. El configurador reúne gráficos, controles, perfiles, idiomas y opciones cooperativas en una ventana propia.

### Descargar e instalar

1. Entra en [la descarga gratuita](https://github.com/The128ReBits/HD-Pack-and-Improvements-for-JediJosh-PC-Port/releases/tag/hd-pack-launch-swrots-v0.4.0) y elige **Pack_Texturas_HD_y_mejoras_by_The128ReBits_PAL-USA_SWROTS-PC_v0.4.0.zip**.
2. Extrae todo su contenido en una carpeta de tu PC.
3. Abre esa carpeta y ejecuta **Instalar Pack HD y mejoras.exe**.
4. Si ya tienes el port funcionando, selecciona su carpeta. Para una instalación nueva, aporta el port v0.4.0 de JediJosh como ZIP/carpeta, tu ISO/XISO de Xbox PAL/USA reconocida y un destino nuevo o vacío.

Las texturas HD ya van incluidas. El juego, la ISO y el port original se aportan por separado. Los enlaces automáticos «Source code» son el código del repositorio; el instalador está en el ZIP para jugadores con el nombre indicado arriba.

### DLSS 5 opcional y experimental

En el configurador, abre **Instalación y DLSS...**, deja marcada la descarga automática y pulsa **Instalar y activar DLSS**. El asistente obtiene los componentes que faltan y verifica sus huellas; también admite una carpeta local completa. Reinicia el juego después. Puedes empezar con **Calidad alta (77 %)** y personalizar o desactivar DLSS desde el mismo asistente. También puedes solicitarlo al instalar el pack.

Es una integración comunitaria con componentes de terceros, incluida la compilación de Lecram. Mi aportación es la integración, el perfil y las herramientas de instalación. El resultado depende del equipo y **HD funciona también sin DLSS**.

### Gracias, JediJosh

Su port nativo, gráficos, sonido, controles, resolución ampliada, panorámico, Yoda/Sith Yoda, herramientas de personajes, duelos, cooperativo original, cámara libre y base para modding hacen posible este pack. Gracias por compartir el código, las herramientas y la investigación con la comunidad. Las texturas HD y las mejoras añadidas por este paquete son de **The128ReBits**; el juego original es de The Collective y LucasArts.

**30 FPS recomendados para historia; superiores experimentales.** La cobertura HD es parcial y las capacidades varían por personaje. Consulta las limitaciones de droideka, lanzallamas y andador antes de jugar. Esta revisión del empaquetado no recibió una nueva partida completa ni validación en GPU.

[README completo en español](README_ES.md) · [Guía de instalación](GUIA_ES.txt) · [Cambios y mejoras](CAMBIOS_ES.txt) · [Créditos](CREDITOS_ES.txt) · [Descargar en ModDB](https://www.moddb.com/mods/revenge-of-the-sith-hd-pack-for-jedijoshs-pc-port/downloads/revenge-of-the-sith-hd-pack-pc-pal-usa)


### Sigue el proyecto

El pack es gratuito. [YouTube: partidas y novedades](https://www.youtube.com/@The128ReBits) · [Ko-fi](https://ko-fi.com/the128rebits) · [Patreon](https://www.patreon.com/The128ReBits). El apoyo es voluntario.




</details>
