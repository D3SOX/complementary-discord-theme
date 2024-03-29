<div align="center" justify="center">

<h2> 🧩 Complementary 🧩 </h2>

A Discord theme which only provides some QOL enhancements that can be used in addition to others

</div>

# 🎉 Features

- [Server Columns](https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/ServerColumns)
- [Settings Icons](https://github.com/D3SOX/SettingsIcons)
- [JoyPixels emojis](https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/EmojiReplace)
- Collapsed Search Bar
- [Hide Nitro upselling](hide-nitro-upselling.theme.scss) (Disclaimer: I am using the [Vencord FakeNitro plugin](https://vencord.dev/plugins/FakeNitro) so it doesn't cover these cases)
- Hide Help Button
- Custom Fonts

# ❕ Required Fonts

- [SF Pro Display](https://developer.apple.com/fonts/)
- [SF Mono](https://developer.apple.com/fonts/) _(For codeblocks)_

If you are on Arch Linux just install [`otf-san-francisco`](https://aur.archlinux.org/packages/otf-san-francisco) and [`otf-san-francisco-mono`](https://aur.archlinux.org/packages/otf-san-francisco-mono) with your favorite AUR helper. Otherwise download, extract and install them manually (e.g. using 7-Zip)

# 📥 Installation

<details>

<summary>
If you want the features listed above click here
</summary>

- [Vencord](https://github.com/Vendicated/Vencord)
  - Open settings, click on Themes under Vencord then click on Online Themes
  - Add a new line with this content: `https://d3sox.me/complementary-discord-theme/complementary.theme.css`
- [OpenAsar](https://github.com/GooseMod/OpenAsar)
  - Open settings, scroll to the bottom on the left and click on the OpenAsar version, then click on Theming
  - Add a new line with this content: `@import url(https://d3sox.me/complementary-discord-theme/complementary.theme.css);`

- [Replugged](https://github.com/replugged-org/replugged)
  - Open your themes folder and clone this repository
    ```sh
    git clone https://github.com/D3SOX/complementary-discord-theme
    ```

- [BetterDiscord](https://github.com/BetterDiscord/BetterDiscord)

  - Drop the [`complementary.betterdiscord.theme.css`](https://raw.githubusercontent.com/D3SOX/complementary-discord-theme/master/complementary.betterdiscord.theme.css) in your themes folder

</details>

<details>

<summary>
If you only want the Nitro upselling styles click here
</summary>

- [Vencord](https://github.com/Vendicated/Vencord)
  - Open settings, click on Themes under Vencord then click on Online Themes
  - Add a new line with this content: `https://d3sox.me/complementary-discord-theme/hide-nitro-upselling.theme.css`
- [OpenAsar](https://github.com/GooseMod/OpenAsar)
  - Open settings, scroll to the bottom on the left and click on the OpenAsar version, then click on Theming
  - Add a new line with this content: `@import url(https://d3sox.me/complementary-discord-theme/hide-nitro-upselling.theme.css);`

- [Replugged](https://github.com/replugged-org/replugged)
  - Open your themes folder and clone this repository
    ```sh
    git clone https://github.com/D3SOX/complementary-discord-theme
    ```
  - Change `complementary.theme.css` to `hide-nitro-upselling.theme.css` in `complementary-discord-theme/manifest.json`

- [BetterDiscord](https://github.com/BetterDiscord/BetterDiscord)

  - Drop the [`hide-nitro-upselling.betterdiscord.theme.css`](https://raw.githubusercontent.com/D3SOX/complementary-discord-theme/master/hide-nitro-upselling.betterdiscord.theme.css) in your themes folder

</details>

# 🧮 Customize Server Columns

Add and adjust the following CSS
```css
:root {
  --columns: 2;
  --guildsize: 40;
  --guildgap: 3;
  --aligndms: 0;
}
```
