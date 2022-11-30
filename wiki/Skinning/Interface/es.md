# Skinning de la interfaz

*Ver tambien: [Interface](/wiki/Client/Interface)*

Interface skinning elements are used in multiple game modes or parts of the client's user interface.

## Menu principal

`menu-background.jpg`

![](img/menu-background.jpg)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 1366x768 (ver notas) |

Notas:

- [osu!supporter](/wiki/osu!supporter) requerido.
- This element is positioned in the centre and is set to cover (fill the entire width and height while keeping its aspect ratio, but crop anything that is outside the game window).
- By default, osu! has a set of background images that it will cycle through.
  - If this element is skinned and the user has osu!supporter tag, this element will override this behaviour.
- This element is used as the playfield if beatmap does not have a background.
- The seasonal background option can affect the visibility of this element.
  - If it is set to `Always` the seasonal backgrounds will override this element.
  - If it is set to `Sometimes` the seasonal backgrounds will override this element while they are in active use.
- `.jpg` extension only.
  - If the image type is `.png` change the extension to `.jpg`.
    - If the background is transparent, the background colour will be black.
- The player can drag and drop an image to overwrite the skin's skinned image. **This will replace the image in the skin's folder!**

---

`welcome_text.png`

![](img/welcome_text.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- [osu!supporter](/wiki/osu!supporter) requerido.
- This element appears upon starting the client.
- This element folds out and expands, then fades out.

---

`menu-snow.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- If not skinned, the current game mode's small icon will be used instead.
- Must be enabled in the [options](/wiki/Client/Options) to see.
  - This option may forcibly be enabled during the holidays (Christmas).

## Button

`button-left.png`

![](img/button-left.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Esquinoa Superior Derecha | - |

Notas:

- Use same height as other button pieces.
- Tinting varies by button state.

---

`button-middle.png`

![](img/button-middle.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Superior | - |

Notas:

- This element is stretched to fit the needed width.
- Use same height as other button pieces.
- Tinting varies by button state.

---

`button-right.png`

![](img/button-right.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Esquina Superior Izquierda | - |

Notas:

- Use same height as other button pieces.
- Tinting varies by button state.

## Cursor

`cursor.png`

![](img/cursor.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- By default, this element will rotate and expand (on click).
- [skin.ini](/wiki/Skinning/skin.ini) commands:
  - To disable cursor expand (on click), set `CursorExpand` to `0`.
  - To disable cursor rotate, set `CursorRotate` to `0`.

---

`cursormiddle.png`

![](img/cursormiddle.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This element does not rotate nor expand (on click).
- This element is above the `cursor.png` element.

---

`cursor-smoke.png`

![](img/cursor-smoke.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This element is used when the player presses the smoke key.
  - By default, the smoke key is bound to `C`.

---

`cursortrail.png`

![](img/cursortrail.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This element is underneath the `cursor.png` element
- If `cursormiddle.png` is present, a longer trail is used.
- By default, this element does not rotate.
- [skin.ini](/wiki/Skinning/skin.ini) command:
  - To enable cursortrail rotate, set `CursorTrailRotate` to `1`.

---

`cursor-ripple.png`

![](img/cursor-ripple.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | unknown | Aditivo | Centro | - |

Notas:

- This element is used when the player presses the Left-Click key or Right-Click key on their keyboard or mouse.
  - By default, the Left-Click key is bound to `Z`.
  - By default, the Right-Click key is bound to `X`.

## Mod icons

*Main page: [Game Modifiers](/wiki/Game_modifier)*

---

`selection-mod-autoplay.png`

![](img/selection-mod-autoplay.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-cinema.png`

![](img/selection-mod-cinema.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Click the Auto mod icon to see this icon.

---

`selection-mod-doubletime.png`

![](img/selection-mod-doubletime.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-easy.png`

![](img/selection-mod-easy.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-fadein.png`

![](img/selection-mod-fadein.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.

---

`selection-mod-flashlight.png`

![](img/selection-mod-flashlight.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-halftime.png`

![](img/selection-mod-halftime.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-hardrock.png`

![](img/selection-mod-hardrock.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-hidden.png`

![](img/selection-mod-hidden.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- For [osu!mania](/wiki/Game_mode/osu!mania), click the Fade In mod icon to see this icon.

---

`selection-mod-key1.png`

![](img/selection-mod-key1.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.
- Cycle through the xK mods to view.

---

`selection-mod-key2.png`

![](img/selection-mod-key2.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.
- Cycle through the xK mods to view.

---

`selection-mod-key3.png`

![](img/selection-mod-key3.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.
- Cycle through the xK mods to view.

---

`selection-mod-key4.png`

![](img/selection-mod-key4.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.

---

`selection-mod-key5.png`

![](img/selection-mod-key5.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.
- Cycle through the xK mods to view.

---

`selection-mod-key6.png`

![](img/selection-mod-key6.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.
- Cycle through the xK mods to view.

---

`selection-mod-key7.png`

![](img/selection-mod-key7.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.
- Cycle through the xK mods to view.

---

`selection-mod-key8.png`

![](img/selection-mod-key8.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.
- Cycle through the xK mods to view.

---

`selection-mod-key9.png`

![](img/selection-mod-key9.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.
- Cycle through the xK mods to view.

---

`selection-mod-keycoop.png`

![](img/selection-mod-keycoop.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.

---

`selection-mod-mirror.png`

![](img/selection-mod-mirror.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.

---

`selection-mod-nightcore.png`

![](img/selection-mod-nightcore.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Click the Double Time mod icon to see this icon.

---

`selection-mod-nofail.png`

![](img/selection-mod-nofail.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-perfect.png`

![](img/selection-mod-perfect.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- Click the Sudden Death mod icon to see this icon.

---

`selection-mod-random.png`

![](img/selection-mod-random.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!mania](/wiki/Game_mode/osu!mania)-specific.

---

`selection-mod-relax.png`

![](img/selection-mod-relax.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!](/wiki/Game_mode/osu!), [osu!taiko](/wiki/Game_mode/osu!taiko), and [osu!catch](/wiki/Game_mode/osu!catch)-specific mod.

---

`selection-mod-relax2.png`

![](img/selection-mod-relax2.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!](/wiki/Game_mode/osu!)-specific mod.
- This mod will move the cursor for the player while the player just needs to tap or click.

---

`selection-mod-scorev2.png`

![](img/selection-mod-scorev2.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-spunout.png`

![](img/selection-mod-spunout.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

Notas:

- This element is [osu!](/wiki/Game_mode/osu!)-specific mod.

---

`selection-mod-suddendeath.png`

![](img/selection-mod-suddendeath.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

---

`selection-mod-target.png`

![](img/selection-mod-target.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

- This mod is available in the cuttingedge stream only.
- This element is an [osu!](/wiki/Game_mode/osu!)-specific mod.

---

`selection-mod-freemodallowed.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

- This mod does not have an image in-game.
- This mod does not show up in the mod selection or leaderboards.
- Indicator for plays with certain mods and combinations.
  - Does not show up if only 'Score V2', 'Auto', 'Double Time', 'Nightcore', or 'Half Time' by itself is used, combinations with other mods including them will show the mod.

---

`selection-mod-touchdevice.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 64x64 |

- This mod does not have an image in-game.
- This mod does not show up in the mod selection.
- Indicator for plays done using a touchscreen.
  - The client uses a background algorithm to calculate if a play is done with a touchscreen, if too many cursor warps occur it might be applied to a play.

## Offset wizard

*Main page: [Offset Wizard](/wiki/Guides/How_to_Use_the_Offset_Wizard)*

---

`options-offset-tick.png`

![](img/options-offset-tick.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Centro | - |

Notas:

- Tinting varies by tick state.

## Playfield

`play-skip.png`

![](img/play-skip.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] | ![Yes][true] | Multiplicativo | Bottom Right | - |

Notas:

- Animation name: `play-skip-{n}.png`

---

`play-unranked.png`

![](img/play-unranked.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Centro | - |

Notas:

- This element is shown when using mods that disable score submission.

---

`play-warningarrow.png`

![](img/play-warningarrow.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] (see notes) | Multiplicativo | Centro | - |

Notas:

- Beatmap skinnable status is suspected to be a bug.
- Tinting varies by version.
  - pause screen:
    - all versions: tinted blue
  - exiting breaks:
    - v1.0: tinted white
    - v2.0+: tinted red

---

`arrow-pause.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] (see notes) | Normal | Centro | - |

Notas:

- Beatmap skinnable status is suspected to be a bug.
- If skinned, this element overrides `play-warningarrow.png`.
- This element is used in the pause and fail screens.
- Not tinted.

---

`arrow-warning.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] (see notes) | Normal | Centro | - |

Notas:

- Beatmap skinnable status is suspected to be a bug.
- If skinned, this element overrides `play-warningarrow.png`.
- Used for the end break warning.
- Not tinted.

---

`masking-border.png`

![](img/masking-border.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Right | max height: 768px |

Notas:

- Used when playing with 4:3 storyboards on widescreen.
- While beatmapping, disable `Widescreen support` in [song setup](/wiki/Client/Beatmap_editor/Song_Setup) for this to appear.
- This element is stretched to fit the needed area.
- The right pillar is flipped horizontally.

---

`multi-skipped.png`

![](img/multi-skipped.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Bottom Right | 60x30 |

Notas:

- This element is used in multi games, seen next to the player's score (on the sides) when the player votes to skip the intro of a beatmap.

---

`section-fail.png`

![](img/section-fail.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This element is seen when the player has a low amount of HP, about less than 50%, during a long enough break.

---

`section-pass.png`

![](img/section-pass.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This element is seen when the player has a high amount of HP, about more than 50%, during a long enough break.

### Countdown

`count1.png`

![](img/count1.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Centro | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This should either say "1" or "3".

---

`count2.png`

![](img/count2.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Right | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This should say "2".

---

`count3.png`

![](img/count3.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![Yes][true] | Normal | Left | - |
| 2.0+ | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This should either say "3" or "1".

---

`go.png`

![](img/go.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This should say "Go!".

---

`ready.png`

![](img/ready.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This should say "Are You Ready?" or "Ready?".

### Hit bursts

*Main page: [Skinning/FAQ § Ranking screen hierarchy](/wiki/Skinning/FAQ#ranking-screen-hit-score-hierarchy)*

---

`hit0.png`

![](/wiki/shared/judgement/osu!/hit0.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit0-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit50.png`

![](/wiki/shared/judgement/osu!/hit50.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit50-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit100.png`

![](/wiki/shared/judgement/osu!/hit100.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit100-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit100k.png`

![](/wiki/shared/judgement/osu!/hit100k.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit100k-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300.png`

![](/wiki/shared/judgement/osu!/hit300.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit300-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300g.png`

![](/wiki/shared/judgement/osu!/hit300g.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit300g-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.

---

`hit300k.png`

![](/wiki/shared/judgement/osu!/hit300k.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] (see notes) | ![Yes][true] | Normal | Centro | - |

Notas:

- Animation name: `hit300k-{n}.png`
- Animation rate is fixed to 60 FPS.
- If animation is used:
  - animation does not loop, but the last frame persists until it fades out.
  - single frame behaviour is not used.
- This element is not shown on the ranking screen.

### Input overlay

`inputoverlay-background.png`

![](img/inputoverlay-background.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Esquinoa Superior Derecha | 193x55 |

Notas:

- This element is positioned at 320px height.
- Since the image is rotated, the origin on the image itself is Top Left.
- This element is used in [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch).
- This element is rotated 90 degrees clockwise and stretched by 1.05x in-game.
- Must be enabled in the [options](/wiki/Client/Options) to see.

---

`inputoverlay-key.png`

![](img/inputoverlay-key.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Centro | 43x46 |

Notas:

- This element is used in [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch).
- Positioning varies for each key:
  - 24px away from screenborder
  - K1/L: at 350px height
  - K2/R: at 398px height
  - M1/D: at 446px height
  - M2: at 492px height
- Toggleable in the [options](/wiki/Client/Options).
- Shrinks briefly when the keys are pressed.
- Tinting varies by button location and state:
  - White, if key is not pressed.
  - Yellow, if the key is pressed and located on the top half.
  - Purple, if the key is pressed and located on the bottom half.

### Pause screen

`pause-overlay.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 1366x768 |

Notas:

- When the game is paused, the playfield will be dimmed and this file will overlay on top of it.
- This element will not stretch to fit.
- Full image height is 768px.
- Smaller images are shown with transparent borders while larger images are partially shown.
- This can also be a `.jpg` file (and can have the `.jpg` extension).
  - osu! prefers `.png` over `.jpg`.

---

`fail-background.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | 1366x768 |

Notas:

- When the player has failed, the playfield will be dimmed and this file will overlay on top of it.
- This element will stretch to fit.
- This can also be a `.jpg` file (and can have the `.jpg` extension).
  - osu! prefers `.png` over `.jpg`.

---

`pause-back.png`

![](img/pause-back.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- This element is positioned at 576px height.
- This element is seen in the fail and pause screens.

---

`pause-continue.png`

![](img/pause-continue.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

- This element is positioned at 224px height.
- This element is seen in the pause screen.

---

`pause-replay.png`

![](img/pause-replay.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Right | - |

Notas:

- This element appears on the ranking screen (after finishing a map or viewing a score).
- This element is positioned at 672px height or at 576px height, if `pause-retry.png` is not available.

---

`pause-retry.png`

![](img/pause-retry.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | - |

Notas:

- Positioning varies:
  - pause or fail screen:
    - Centre, positioned at 400px height
  - ranking screen:
    - Right, positioned at 576px height
- This element appears on the ranking screen after finishing a map and on the pause and fail screens.

### Scorebar

`scorebar-bg.png`

![](img/scorebar-bg.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Esquina Superior Izquierda | - |

Notas:

- This element has no size restrictions.
- When used in [osu!mania](/wiki/Game_mode/osu!mania), this element is rotated 90 degrees anti-clockwise and is placed at the bottom right of stage.

---

`scorebar-colour.png`

![](img/scorebar-colour.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] | ![Yes][true] | (Varies) | Esquina Superior Izquierda | max height: 120px |

Notas:

- Animation name: `scorebar-colour-{n}.png`.
- Blend mode varies:
  - Multiplicative, if `scorebar-marker.png` is used.
    - Tinted black over time when near critical zone and tinted red in the critical zone.
  - Normal, otherwise.
- Positioning varies:
  - If a marker is used, positioned at (12,12).
  - Otherwise, positioned at (5,16).
- This element has no size restrictions.
- When used in [osu!mania](/wiki/Game_mode/osu!mania), this element is rotated 90 degrees anti-clockwise and is placed at the bottom right of stage.

---

`scorebar-ki.png`

![](img/scorebar-ki.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- `scorebar-marker.png` has higher priority.
- This element represents the "passing" zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania).
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`
- A `scorebar-colour.png` is required for this element to appear.

---

`scorebar-kidanger.png`

![](img/scorebar-kidanger.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- `scorebar-marker.png` has higher priority.
- this element represents the "warning" zone
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania)
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`
- A `scorebar-colour.png` is required for this element to appear.

---

`scorebar-kidanger2.png`

![](img/scorebar-kidanger2.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | Centro | - |

Notas:

- `scorebar-marker.png` has higher priority.
- This element represents the "critical" zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania)
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`
- A `scorebar-colour.png` is required for this element to appear.

---

`scorebar-marker.png`

![](img/scorebar-marker.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Aditivo | Centro | - |

Notas:

- If skinned, this element overrides the `scorebar-ki.png`, `scorebar-kidanger.png`, and `scorebar-kidanger2.png` elements.
- The marker fades out if the player reaches the critical zone.
- This element is not used in [osu!mania](/wiki/Game_mode/osu!mania).
- Y-position at 16; x-position is placed at the end of the cropped `scorebar-colour.png`.

### Score numbers

`score-0.png`

![](img/score-0.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-1.png`

![](img/score-1.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-2.png`

![](img/score-2.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-3.png`

![](img/score-3.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-4.png`

![](img/score-4.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-5.png`

![](img/score-5.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-6.png`

![](img/score-6.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-7.png`

![](img/score-7.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-8.png`

![](img/score-8.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-9.png`

![](img/score-9.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | - |

Notas:

- By default, this is also used for the combo numbers.
- Blend mode varies:
  - If used for combo counter:
    - In [osu!](/wiki/Game_mode/osu!) and [osu!catch](/wiki/Game_mode/osu!catch), additive for the expanding after images.
    - Additionally in osu!catch, the after images are tinted using the combo colour of the fruit.
    - In osu!mania, multiplicative.

---

`score-comma.png`

![](img/score-comma.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 5x14 |

Notas:

- By default, this is also used for the combo numbers.
- This element is for the accuracy.
- The usage is dependent on your selected language.

---

`score-dot.png`

![](img/score-dot.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 5x14 |

Notas:

- By default, this is also used for the combo numbers.
- This element is for the accuracy.
- The usage is dependent on your selected language.

---

`score-percent.png`

![](img/score-percent.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 12x14 |

Notas:

- This element is for the accuracy.

---

`score-x.png`

![](img/score-x.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | (Varies) | (Varies) | 10x14 |

Notas:

- This element is for the combo, only used in [osu!](/wiki/Game_mode/osu!).
- Blend mode varies:
  - If used for combo counter:
    - Additive for the expanding after images.

## Ranking grades

`ranking-XH.png`

![](img/ranking-XH.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screenborder
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-XH-small.png`

![](img/ranking-XH-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-X.png`

![](img/ranking-X.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screenborder
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-X-small.png`

![](img/ranking-X-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-SH.png`

![](img/ranking-SH.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-SH-small.png`

![](img/ranking-SH-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-S.png`

![](img/ranking-S.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-S-small.png`

![](img/ranking-S-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-A.png`

![](img/ranking-A.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-A-small.png`

![](img/ranking-A-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-B.png`

![](img/ranking-B.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-B-small.png`

![](img/ranking-B-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-C.png`

![](img/ranking-C.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-C-small.png`

![](img/ranking-C-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

---

`ranking-D.png`

![](img/ranking-D.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | - |

Notas:

- Positioning varies:
  - 192px away from right screen border
  - v1.0: at 272px height
  - v2.0+: at 320px height

---

`ranking-D-small.png`

![](img/ranking-D-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Normal | (Varies) | 34x40 |

Notas:

- Origin varies:
  - Break: Centre
  - Song Select panel: Left
  - User scores: Centre

## Ranking screen

`ranking-accuracy.png`

![](img/ranking-accuracy.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] (see notes) | ![No][false] | Normal | Esquina Superior Izquierda | - |

Notas:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-accuracy-{n}.png`
- Positioning varies:
  - v1.0: (291,500)
  - v2.0+: (291,480)

---

`ranking-graph.png`

![](img/ranking-graph.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | min: 308x156 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | min: 308x148 |

Notas:

- Positioning varies:
  - v1.0: (256,576)
  - v2.0+: (256,608)
- The box itself is 301x141.
- The first 7 pixels at the top and at the left should be transparent.
  - In v1 it's shifted down by 8px.

---

`ranking-maxcombo.png`

![](img/ranking-maxcombo.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] (see notes) | ![No][false] | Normal | Esquina Superior Izquierda | - |

Notas:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-maxcombo-{n}.png`
- Positioning varies:
  - v1.0: (8,500)
  - v2.0+: (8,480)

---

`ranking-panel.png`

![](img/ranking-panel.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | max height: 694px |
| 2.0+ | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | max height: 666px |

Notas:

- Positioning varies:
  - v1.0: (0,74)
  - v2.0+: (0,102)

---

`ranking-perfect.png`

![](img/ranking-perfect.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] (see notes) | ![No][false] | Normal | Centro | - |

Notas:

- Can be animated, but only the zeroth frame will be used.
  - Animation name: `ranking-perfect-{n}.png`
- Positioning varies:
  - v1.0: (320,688)
  - v2.0+: (416,688)

---

`ranking-title.png`

![](img/ranking-title.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Esquinoa Superior Derecha | - |

Notas:

- x-position 32px away from the right side

---

`ranking-replay.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Right | - |

Notas:

- Position varies:
  - at 672px height.
  - at 576px height, if retry is not available.

---

`ranking-retry.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Right | - |

Notas:

- Positioned at 576px height.
- If skinned, this element overrides `pause-retry.png`.

---

`ranking-winner.png`

![](img/ranking-winner.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 200x214 |

Notas:

- This element is used in [multi](/wiki/Client/Interface/Multiplayer) only.

## Score entry

`scoreentry-0.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-1.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-2.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-3.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-4.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-5.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-6.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-7.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-8.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-9.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 11x14 |

Notas:

- This element is used for the in-game leaderboards and input overlay.
  - For input overlay, the initial button labels are not skinnable.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
  - Input overlay: use `InputOverlayText` value from [skin.ini](/wiki/Skinning/skin.ini) or black, if not defined
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right
  - Rank: Top Right
  - Input overlay: Top

---

`scoreentry-comma.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | (varies) | 5x14 |

Notas:

- This element is used for the in-game leaderboards.
- This element is used as the decimal separator.
  - Usage depends on your selected language.
- Tinting depends on use:
  - Score: white
  - Combo: cyan
- Origin varies on use:
  - Score: Top Left
  - Combo: Top Right

---

`scoreentry-dot.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Esquina Superior Izquierda | 5x14 |

Notas:

- This element is used for the in-game leaderboards.
- This element is used as the decimal separator.
  - Usage depends on your selected language.
- Tinted white.

---

`scoreentry-percent.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Esquina Superior Izquierda | 12x14 |

Notas:

- This element is used for the in-game leaderboards.
- This element is used in [Multi](/wiki/Client/Interface/Multiplayer) games when the win condition is set to Accuracy.
- Tinted white.

---

`scoreentry-x.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Esquinoa Superior Derecha | 10x14 |

Notas:

- This element is used for the in-game leaderboards.
- This element is used as the multiplier symbol.
- Tinted cyan.

## Song selection

`menu-back.png`

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![Yes][true] | ![No][false] | Normal | Bottom Left | 200x214 |

Notas:

- Animation name: `menu-back-{n}.png`.
- The native back button is not skinnable.
  - If this element is skinned, it will override the new one everywhere, except for the [options](/wiki/Client/Options).

---

`menu-button-background.png`

![](img/menu-button-background.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Bottom Left | min: 690x85 |

Notas:

- Skin versions 2.2+ can support thumbnails (must be enabled in the [options](/wiki/Client/Options)) for song selection
  - Thumbnails get positioned 9px away from the left image border
  - Thumbnail size is 115x85
- This element is used in various places:
  - scoreboards in song selection
  - button for the beatmap difficulty in song selection
  - scoreboards on the left while playing
  - button that shows the selected beatmap while waiting in a room in multiplayer
- Tinting varies by button state.

---

`selection-mode.png`

![](img/selection-mode.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 92x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 92x90 |

Notas:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-mode-over.png`

![](img/selection-mode-over.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 92x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 92x90 |

Notas:

- Hover over `selection-mode.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-mods.png`

![](img/selection-mods.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-mods-over.png`

![](img/selection-mods-over.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- Hover over `selection-mods.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-random.png`

![](img/selection-random.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-random-over.png`

![](img/selection-random-over.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- Hover over `selection-random.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-options.png`

![](img/selection-options.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- In v1.0, positioning is 87px away from the bottom.

---

`selection-options-over.png`

![](img/selection-options-over.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 1.0 | ![No][false] | ![No][false] | Normal | Esquina Superior Izquierda | 77x87 |
| 2.0+ | ![No][false] | ![No][false] | Normal | Bottom Left | 77x90 |

Notas:

- Hover over `selection-options.png` to see.
- In v1.0, positioning is 87px away from the bottom.

---

`selection-tab.png`

![](img/selection-tab.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Multiplicativo | Esquina Superior Izquierda | 142x24 |

Notas:

- Depending on the client's window size, 4 to 5 tabs will be displayed.

---

`star.png`

![](img/star.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Multiplicativo | Centro | 50x50 |

Notas:

- This element is used for difficulty star ratings (seen in song selection).
  - v2.2+ will scale down the last star, if necessary
  - v2.1- will crop the last star, if necessary
- Tinting depends on the state of `menu-button-background.png`

---

`star2.png`

![](img/star2.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![Yes][true] | Aditivo | Centro | 24x24 |

Notas:

- This element is used for song selection (the stars that fly from right to left), cursor, kiai time, combobursts.

### Mode select

`mode-osu.png`

![](img/mode-osu.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 256x256 |

Notas:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!](/wiki/Game_mode/osu!) for this to be visible.

---

`mode-taiko.png`

![](img/mode-taiko.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 256x256 |

Notas:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!taiko](/wiki/Game_mode/osu!taiko) for this to be visible.

---

`mode-fruits.png`

![](img/mode-fruits.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 256x256 |

Notas:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!catch](/wiki/Game_mode/osu!catch) for this to be visible.

---

`mode-mania.png`

![](img/mode-mania.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 256x256 |

Notas:

- This element flashes in the centre of the song select screen in respect of the song's BPM.
- Select [osu!mania](/wiki/Game_mode/osu!mania) for this to be visible.

---

`mode-osu-med.png`

![](img/mode-osu-med.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 128x128 |

Notas:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-taiko-med.png`

![](img/mode-taiko-med.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 128x128 |

Notas:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-fruits-med.png`

![](img/mode-fruits-med.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 128x128 |

Notas:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-mania-med.png`

![](img/mode-mania-med.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Normal | Centro | 128x128 |

Notas:

- This element is used inside the game mode selection dropdown menu.
- Click on `selection-mode.png` to see.

---

`mode-osu-small.png`

![](img/mode-osu-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- This element is on top of the `selection-mode.png` element.
- Select [osu!](/wiki/Game_mode/osu!) for this to be visible.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-taiko-small.png`

![](img/mode-taiko-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- This element is on top of the `selection-mode.png` element.
- Select [osu!taiko](/wiki/Game_mode/osu!taiko) for this to be visible.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-fruits-small.png`

![](img/mode-fruits-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- This element is on top of the `selection-mode.png` element.
- Select [osu!catch](/wiki/Game_mode/osu!catch) for this to be visible.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

---

`mode-mania-small.png`

![](img/mode-mania-small.png)

| Versiones | Animable | Skin de mapa | Modo de fusión | Origen | Tamaño sugerido (SD) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| Todas | ![No][false] | ![No][false] | Aditivo | Centro | 32x32 |

Notas:

- This element is on top of the `selection-mode.png` element.
- Select [osu!mania](/wiki/Game_mode/osu!mania) for this to be visible.
- If the `menu-snow.png` element is not skinned, this element will be used if it is selected.

[true]: /wiki/shared/true.png
[false]: /wiki/shared/false.png
