[backgroundless]:   https://saltthemerevivalproject.github.io/Synthesis/preview/synthesis1.png
[backgrounded]:     https://saltthemerevivalproject.github.io/Synthesis/preview/synthesis2.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/rgb
[discord]:          https://discord.gg/NNXFh3bEUK

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://vencord.dev/

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[release-css-gh]:     https://img.shields.io/github/downloads/SaltThemeRevivalProject/Synthesis/Synthesis.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/SaltThemeRevivalProject/Synthesis/net.saltssaumure.Synthesis.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/SaltThemeRevivalProject/Synthesis?label=Repository&style=flat-square

[github]:           https://github.com/SaltThemeRevivalProject/Synthesis
[license]:          https://github.com/SaltThemeRevivalProject/Synthesis/blob/main/LICENSE
[issues]:           https://github.com/SaltThemeRevivalProject/Synthesis/issues
[.theme.css]:       https://github.com/SaltThemeRevivalProject/Synthesis/blob/main/Synthesis.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=770 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Synthesis "Replugged store page"
[release-css-gh]:    https://github.com/SaltThemeRevivalProject/Synthesis/releases/latest/download/Synthesis.theme.css "Get latest release"
[release-rp-gh]:    https://github.com/SaltThemeRevivalProject/Synthesis/releases/latest/download/net.saltssaumure.Synthesis.asar "Get latest release"

[backgrounds]:      https://github.com/SaltThemeRevivalProject/Synthesis/tree/main/backgrounds

# Synthesis Discord Theme
[![Buy the original creator a coffee on ko-fi][shield-donate]][ko-fi]
[![CSS GitHub downloads][release-css-gh]][release-css-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***A vibrant neon synthwave Discord theme.***

This is a fork of the [original](https://github.com/Saltssaumure/synthesis-discord-theme) by Saltssaumure which is currently abandoned.

| Without background                              | With background                                                     |
| ----------------------------------------------- | ------------------------------------------------------------------- |
| ![Synthesis applied to Discord][backgroundless] | ![Synthesis with background image applied to Discord][backgrounded] |

## Installation

### [BetterDiscord][BetterDiscord]
<details><summary>Click to expand</summary>

1. Download `Synthesis.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.
</details>

### [Replugged][Replugged]
<details><summary>Click to expand</summary>

#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.Synthesis.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.
</details>

### [Vencord][Vencord]
<details><summary>Click to expand</summary>

#### Local
1. Download `Synthesis.theme.css`:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://saltthemerevivalproject.github.io/Synthesis/Synthesis.theme.css`
</details>

## Customisation
| Variable name                           | Description                | Valid values                                                              | Default value                                                                          |
| --------------------------------------- | -------------------------- | ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| `--synth-background-image`              | Background image           | Image link encased in `url()` or `none`. [Suggested images][backgrounds]. | `url(https://saltthemerevivalproject.github.io/Synthesis/backgrounds/default.avif)` |
| `--synth-backdrop-opacity`              | Backdrop opacity           | A number `0`-`1`.                                                         | `0.3`                                                                                  |
| `--synth-overlay-color`                 | Overlay tint colour        | Space-separated [`RGB`][css-color] value.                                 | `255 165 0  `                                                                          |
| `--synth-crt-light`, `--synth-crt-dark` | CRT scanline colour        | Space-separated [`RGB`][css-color] value.                                 | `255 255 255`, `0   0   0`                                                             |
| `--synth-crt-flicker`                   | &#9888; CRT flicker effect | `flicker` (on) or `none` (off)                                            | `none`                                                                                 |
| `--synth-color-background`              | Background colour          | Space-separated [`RGB`][css-color] value.                                 | `20  6   36 `                                                                          |
| `--synth-color-foreground`              | Foreground colour          | Space-separated [`RGB`][css-color] value.                                 | `255 165 0  `                                                                          |
| `--synth-color-shadow`                  | Shadow colour              | Space-separated [`RGB`][css-color] value.                                 | `0   0   128`                                                                          |
| `--synth-color-button`                  | Button colour              | Space-separated [`RGB`][css-color] value.                                 | `84  63  251`                                                                          |
| `--synth-color-pop`                     | Highlight colour           | Space-separated [`RGB`][css-color] value.                                 | `206 63  251`                                                                          |
| `--synth-color-blurple`                 | Discord colour             | Space-separated [`RGB`][css-color] value.                                 | `88  101 242`                                                                          |
| `--synth-color-text`                    | Text colour                | Space-separated [`RGB`][css-color] value.                                 | `255 255 255`                                                                          |
| `--synth-color-red`                     | DND colour                 | Space-separated [`RGB`][css-color] value.                                 | `243 67  131`                                                                          |
| `--synth-color-yellow`                  | Idle colour                | Space-separated [`RGB`][css-color] value.                                 | `255 165 0  `                                                                          |
| `--synth-color-green`                   | Online colour              | Space-separated [`RGB`][css-color] value.                                 | `52  172 140`                                                                          |
| `--synth-color-twitch`                  | Streaming colour           | Space-separated [`RGB`][css-color] value.                                 | `89  54  149`                                                                          |

&#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
<details><summary>Click to expand</summary>

1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.
</details>

### Replugged
<details><summary>Click to expand</summary>

1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste line 15-36 of [`Synthesis.theme.css`][.theme.css].
3. Edit the variable values and save.
</details>

### Vencord
<details><summary>Click to expand</summary>

#### Local
2. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
3. Open `Synthesis.theme.css` with your favourite text editor.
4. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-36 of [`Synthesis.theme.css`][.theme.css].
3. Edit the variable values.
</details>

## License
Copyright (c) 2022-2024 Saltssaumure

This theme is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This theme is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU Affero General Public License][license] for more details.

## Credits
### Themes
[radialstatus]: https://github.com/DiscordStyles/RadialStatus

- [RadialStatus][radialstatus] by [DiscordStyles](https://github.com/DiscordStyles) ([Gibbu](https://github.com/Gibbu)) - MIT license

### Fonts
[inter]:        https://github.com/rsms/inter
[firacode]:     https://github.com/tonsky/FiraCode

- [Inter][inter] by [Rasmus Andersson](https://github.com/rsms) - OFL-1.1
- [Fira Code][firacode] by [Nikita Prokopov](https://github.com/tonsky) - OFL-1.1

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in the synthesis channel on [the Discord server][discord].
