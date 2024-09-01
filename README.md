# The ISS Construction Kit
_An ISS parts mod for Kerbal Space Program 2_

> [!NOTE]
> This mod is in pre-release. It does not have all the ISS components yet.

This mod seeks to provide ISS and space modeling enthusiasts with all of the station's components (eventually) so that they can recreate its construction in the historical sequence of assembly, or simply utilize them to construct the space station of their dreams.

![The ISS above a desert](https://github.com/pasalvetti/iss/blob/main/Communication/iss012.png?raw=true)

## Gallery
### Zarya

Zarya, the original 'grandma' of the ISS, started out as the powerhouse, the brains, and the muscle of the station. But now, after years of hard work, she's basically the space version of an attic, filled with random stuff from the early days of space exploration.

![Zarya icon](https://github.com/pasalvetti/iss/blob/main/Icones/iss_zarya_icon.png?raw=true)

### Unity

Unity is the first U.S.-built component of the ISS, linking the laboratory's Russian Orbital Segment and US Orbital Segment. Unity was launched on 4 December 1998, aboard Space Shuttle Endeavour on STS-88.

![Unity icon](https://github.com/pasalvetti/iss/blob/main/Icones/iss_unity_icon.png?raw=true)

### Zvezda

Zvezda provides essential life support systems and offers a cozy home for two lucky kerbonauts. But don't be fooled by its laid-back exterior - Zvezda can be remotely controlled, so if it ever decides to start slacking off, the KSC can give it a virtual kick in the pants.

![Zvezda icon](https://github.com/pasalvetti/iss/blob/main/Icones/iss_zvezda_icon.png?raw=true)

### APAS-95 docking port

APAS-95 is an androgynous docking system used on the American and Russian modules on the ISS and to allow the Space Shuttle to dock.

![APAS-95 icon](https://github.com/pasalvetti/iss/blob/main/Icones/iss_apas-95_icon.png?raw=true)

### CBM docking port

It's the ISS's secret weapon for connecting habitable modules in the US Orbital Segment. It's like the ultimate "stick-it-to-the-man" (or, in this case, the space station) solution.

![CMB icon](https://github.com/pasalvetti/iss/blob/main/Icones/iss_cbm_icon.png?raw=true)

### PMA-1

PMA-1 is basically the space equivalent of a USB adapter, but instead of letting you connect your phone to a laptop, it lets spacecraft connect to the station. Think of it as the ultimate 'space plug-in' for cosmic commuters. Launched with the Unity module in 1998 aboard STS-88.

![PMA-1 icon](https://github.com/pasalvetti/iss/blob/main/Icones/iss_pma1_icon.png?raw=true)

### PMA-2/3

This adapter is used on the ISS to convert a CBM interface to an APAS-95 docking port. PMA-2 was launched with the Unity module in 1998 aboard STS-88. It was outfitted special hardware to allow the shuttles to stay docked longer. PMA-3 was launched in 2000 aboard STS-92.

![PMA-2/3 icon](https://github.com/pasalvetti/iss/blob/main/Icones/iss_pma23_icon.png?raw=true)

### Zvezda Solar Panel

Meet the solar panel that's seen more sunrises than a rooster. This retractable array is more interested in reminiscing about the glory days than tracking the sun. It's like a retired kerbonaut who's content to bask in the sunlight, occasionally muttering something about 'good old Comrade Sol'.

![Zvezda Solar Panel icon](https://github.com/pasalvetti/iss/blob/main/Icones/iss_zvezda_solar_panel_icon.png?raw=true)

## Assembly

For those daring enough to recreate the ISS's assembly in its historical sequence, this is the suggested procedure.

> [!TIP]
> In the absence of Canadarm, the use of tugs is necessary.

| Element                | Launcher[^1]           | Date          | Recommended parts                                                         |
|---|---|---|---|
| Zarya                  | Proton-K               | 1998-11-20    | Zarya, APAS-95 x3, Zvezda Solar Panel[^2] x2, RV-105 RCS x4 (stock)      |
| Unity / PMA-1 / PMA-2  | Space Shuttle (STS-88) | 1998-12-04    | Unity, PMA-1, PMA-2/3, CMB x8, APAS-95 x2                                |
| Zvezda                 | Proton-K               | 2000-07-12    | Zvezda, APAS-95 x4, Zvezda Solar Panel x2, Place-Anywhere RCS x8 (stock) |

[^1]: Launchers are not included in this mod.
[^2]: Zarya solar panels to be included in a future release.

## Pictures

![The first stages of the ISS in orbit](https://github.com/pasalvetti/iss/blob/main/Communication/iss009.png?raw=true)

![A view of the VAB with the first stages of the ISS assembled](https://github.com/pasalvetti/iss/blob/main/Communication/iss008.png?raw=true)

![The Orbiter docked to the ISS](https://github.com/pasalvetti/iss/blob/main/Communication/iss015.png?raw=true)

![A close view of the ISS with the Shuttle docked](https://github.com/pasalvetti/iss/blob/main/Communication/iss016.png?raw=true)

![The Shuttle docked to the Unity](https://github.com/pasalvetti/iss/blob/main/Communication/iss017.png?raw=true)

_(shuttle not included)_

## Disclaimer
This mod features a semi-realistic modeling of the ISS as some liberties were taken with reality in order to allow the parts to integrate properly with the game with reasonable performance.

For example the CBM, used to connect habitable elements in the US Orbital Segment of the ISS, is a non-androgynous system in reality but has been made androgynous in the game for simplicity.
## Known Issues
- RCS not included.
- Parts are not available on the tech tree.
- Zvezda Solar Panel is not self-tracking.
- Zvezda Solar Panel deployment in the VAB is too slow.
- Zarya does not have its own solar panel yet (you can use Zvezda's).
- No reentry effects.
- Kerbals located inside Zvezda do not show on the interior view windows.
## Installation
1. Open the game folder by right-clicking on the game in your Steam library, selecting "Manage," and then clicking "Browse local files."
2. Install the [Space Warp + BepinEx plugin](https://spacedock.info/mod/3277/Space%20Warp%20+%20BepInEx) (available on CKAN).
3. Install the [Patch Manager plugin](https://spacedock.info/mod/3482/Patch%20Manager) (available on CKAN).
4. Download the latest version of The ISS Construction Kit, either on [GitHub](https://github.com/pasalvetti/iss/releases) or on Spacedock.
5. Open the zip file and drag the included BepInEx folder into the game folder (merge folders when asked).
## Dependencies
[Space Warp + BepInEx](https://spacedock.info/mod/3277/Space%20Warp%20+%20BepInEx)

[Patch Manager](https://spacedock.info/mod/3482/Patch%20Manager)
## Links
Spacedock: https://spacedock.info/mod/3709/The%20ISS%20Construction%20Kit

Contact: [KSP 2 Modding Society](https://discord.com/channels/1078696971088433153/1279812626947379304)
## Credits
For some parts of the ISS : NASA (https://github.com/nasa/NASA-3D-Resources), Zer0Frost (https://github.com/Zer0Frost/3D-ISS-for-blender)
Adaptation & mod by Polo
