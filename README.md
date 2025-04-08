<div align="center" justify="center">

<h2> 🧩 Complementary 🧩 </h2>

A Discord theme which only provides some QOL enhancements that can be used in addition to others

</div>

# 🎉 Features

There are 4 variants of the theme
- [Complementary](#complementary)
  - Includes all enhancement that I think everyone likes
  - Includes the Nitro upselling styles (for historical reasons)
- Nitro Upselling
  - Only includes the Nitro upselling styles
- [Personal QOL](#personal-qol)
  - Includes some more enhancements that I personally like
- [Spotify Controls](#spotify-controls)
  - Includes my Spotify controls customizations (Turntable with pause functionality)

## Complementary

- [Settings Icons](https://github.com/MiniDiscordThemes/SettingsIcons)
- Collapsed Search Bar (Currently broken)
- Hide activities on top of members list
- Visual Refresh: Bring back the round server icons
- Visual Refresh: Move chatbar to bottom
- [Hide Nitro upselling](hide-nitro-upselling.theme.scss) (Disclaimer: I am using the [Vencord FakeNitro plugin](https://vencord.dev/plugins/FakeNitro) so it doesn't cover these cases)
- Hide Help Button

## Personal QOL

- [Server Columns](https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/ServerColumns)
- Custom Fonts
- [JoyPixels emojis](https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/EmojiReplace)
- Don't highlight new Emojis
- Remove avatar decorations in chat
- Remove profile effects
- Remove "x in voice" scroll indicator
- Restore old attachment sizing behavior
- Reveal masked hyperlinked
- Remove boosting progressbar

### ❕ Required Fonts

- [SF Pro Display](https://developer.apple.com/fonts/)
- [SF Mono](https://developer.apple.com/fonts/) _(For codeblocks)_

If you are on Arch Linux just install [`otf-san-francisco`](https://aur.archlinux.org/packages/otf-san-francisco) and [`otf-san-francisco-mono`](https://aur.archlinux.org/packages/otf-san-francisco-mono) with your favorite AUR helper. Otherwise download, extract and install them manually (e.g. using 7-Zip)

### 🧮 Customize Server Columns

If you are not a fan of the server columns you can add and adjust the following CSS (set to 1 to revert)
```css
:root {
  --columns: 2;
  --guildsize: 40;
  --guildgap: 3;
  --aligndms: 0;
}
```

## Spotify Controls

- Adds a rotating turntable effect for the Spotify album image
- Background blur and brightness effects for the Spotify player
- Pause functionality for the turntable animation when the track is paused

# 📥 Installation

## [Vencord](https://github.com/Vendicated/Vencord)
- Open settings, click on Themes under Vencord then click on Online Themes
- Add a new line with this content:
    - Complementary: `https://d3sox.me/complementary-discord-theme/complementary.theme.css`
    - Nitro Upselling: `https://d3sox.me/complementary-discord-theme/hide-nitro-upselling.theme.css`
    - Personal QOL: `https://d3sox.me/complementary-discord-theme/personal-qol.theme.css`
    - Spotify Controls: `https://d3sox.me/complementary-discord-theme/spotify-controls.theme.css`

## [OpenAsar](https://github.com/GooseMod/OpenAsar)
- Open settings, scroll to the bottom on the left and click on the OpenAsar version, then click on Theming
- Add a new line at the top with this content:
    - Complementary: `@import url(https://d3sox.me/complementary-discord-theme/complementary.theme.css);`
    - Nitro Upselling: `@import url(https://d3sox.me/complementary-discord-theme/hide-nitro-upselling.theme.css);`
    - Personal QOL: `@import url(https://d3sox.me/complementary-discord-theme/personal-qol.theme.css);`
    - Spotify Controls: `@import url(https://d3sox.me/complementary-discord-theme/spotify-controls.theme.css);`

## [Replugged](https://github.com/replugged-org/replugged)
- Open your themes folder and clone this repository  
(if you want to apply multiple ones clone it multiple times with a different name)
  ```sh
  git clone https://github.com/D3SOX/complementary-discord-theme
  ```
- Set the value of `theme` in `complementary-discord-theme/manifest.json` to the following
  - Complementary: `complementary.theme.css`
  - Nitro Upselling: `hide-nitro-upselling.theme.css`
  - Personal QOL: `personal-qol.theme.css`
  - Spotify Controls: `spotify-controls.theme.css`

## [BetterDiscord](https://github.com/BetterDiscord/BetterDiscord)
- Open your themes folder
- Drop the following CSS in your themes folder (Press <kbd>Ctrl</kbd> + <kbd>S</kbd> to save the file)
  - Complementary: [`complementary.betterdiscord.theme.css`](https://raw.githubusercontent.com/D3SOX/complementary-discord-theme/master/complementary.betterdiscord.theme.css)
  - Nitro Upselling: [`hide-nitro-upselling.betterdiscord.theme.css`](https://raw.githubusercontent.com/D3SOX/complementary-discord-theme/master/hide-nitro-upselling.betterdiscord.theme.css) 
  - Personal QOL: [`personal-qol.betterdiscord.theme.css`](https://raw.githubusercontent.com/D3SOX/complementary-discord-theme/master/personal-qol.betterdiscord.theme.css)
  - Spotify Controls: [`spotify-controls.betterdiscord.theme.css`](https://raw.githubusercontent.com/D3SOX/complementary-discord-theme/master/spotify-controls.betterdiscord.theme.css)
