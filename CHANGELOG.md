# Changelog

## 1.1.1

<details>
<summary>✨ Animated frames</summary>

- Every icon in the status row (FrailtyPlus' injuries and the buffs from TZPPlus, Drinkable and FrailtyMedical) has a moving frame, like FrailtyPlus' own icons: its dashes change a few times a second. The pictures don't blink here.

</details>

## 1.1.0

<details>
<summary>✨ Crosshair, extra health, new tooltips</summary>

- **Crosshair** (off by default): frame + mark styles, size, thickness, opacity, when it shows. Hides while the hand icon shows.
- **Extra health** on the health bar (FrailtyMedical's Racing Heart): a green part of the bar, and the number shows health + extra. `ExtraHealthBar` and `ExtraHealthNumber` settings. The green only covers its own part, so it never mixes into the health part (it used to turn it orange).
- New tooltips for every FrailtyPlus injury, plus **Infected**, **Blooming** and **Paranoid** with their `%` under the icon (pulsing while it goes down).
- Bleeding / Laceration / Fatal Bleeding tooltips name FrailtyMedical's items when it's installed.
- StatusApi 2: `SetExtraHealth`.

</details>

## 1.0.0

<details>
<summary>✨ First release (based on Elad's HUD 1.2.3)</summary>

- **Utility slot** (V81) shown at the right end of the health bar, `[TAB]` text hidden.
- **Mic icon** at the end of the stamina bar while you talk (push to talk and voice activation), red muted icon while your mic is off. 3 styles.
- **Status row** under the health bar: Frailty injuries, UsualScrap Productivity Auto-Injector, icons from other mods (TZPPlus) and the vanilla warnings.
- **Cursor mode** (`middle mouse`): point at a status icon to see what it does.
- **AdvancedCompany head item batteries** with a lamp icon, small row and `CompactBatteryUI`.
- Stamina bar fades to `cyan` while the Productivity Auto-Injector is active.
- Optional number outline, flashlight icon gap.
- Fixed the stamina `/sec` number flickering, errors from modded battery items without a battery, and HUD errors stopping the player update.

</details>
