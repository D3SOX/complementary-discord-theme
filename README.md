<div align="center" justify="center">

<h2> 🧩 Complementary 🧩 </h2>

A Discord theme which only provides some QOL enhancements that can be used on top of the official ones

</div>

# 🎉 Features

- [Server Columns](https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/ServerColumns)
- [Settings Icons](https://github.com/crearts-community/Settings-Icons)
- [Code block Icons](https://github.com/snappercord/codeblock-icons)
- [JoyPixels emojis](https://github.com/mwittrien/BetterDiscordAddons/tree/master/Themes/EmojiReplace)
- Collapsed Search Bar
- Hide Nitro upselling
- Hide Help Button
- Custom Fonts

# ❕ Required Fonts

- [SF Pro Display](https://developer.apple.com/fonts/)
- [SF Mono](https://developer.apple.com/fonts/) _(For codeblocks)_


# 📥 Installation

- [Vencord](https://github.com/Vendicated/Vencord)/[OpenAsar](https://github.com/GooseMod/OpenAsar)
  - Find the CSS Editor
    - Vencord: Open settings, click on Vencord, then on the right side click on "Open QuickCSS File"
    - OpenAsar: Open settings, scroll to the bottom on the left and click on the OpenAsar version, then click on Theming
  - Add a new line with this content: `@import url(https://d3sox.github.io/complementary-discord-theme/complementary.theme.css);` 

- [Powercord](https://github.com/powercord-org/powercord/)/[Replugged](https://github.com/replugged-org/replugged)
  - Open your themes folder and clone this repository
    ```sh
    git clone https://github.com/D3SOX/complementary-discord-theme
    ```

- [BetterDiscord](https://github.com/BetterDiscord/BetterDiscord)

  - Drop the [`complementary.betterdiscord.theme.css`](https://raw.githubusercontent.com/D3SOX/complementary-discord-theme/master/complementary.betterdiscord.theme.css) in your themes folder

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
