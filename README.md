KingCordGx

An Opera GX-inspired Discord theme for Vencord, customized and maintained by xM4j0rPr0bleZx.

KingCordGx combines a dark, translucent interface with purple liquid artwork, neon accents, a custom galaxy Home icon, and the Chakra Petch font.

The theme builds on the upstream OperaGXTheme stylesheet while keeping KingCordGx's configuration, branding, assets, and installation files within this repository.



✨ Features

🌌 Dark, translucent Opera GX-inspired interface

💜 Purple liquid background artwork

⚡ Neon purple accents

🪐 Custom galaxy Discord Home icon

🔤 Chakra Petch typography

🎨 Built on the OperaGXTheme engine

📦 Supports local .theme.css installation

🌐 Supports Vencord Online Themes

📥 Vencord Installation

Option 1 — Local Theme File

Download the KingCordGx theme file.

Open Discord.

Go to:User Settings → Vencord → Themes

Under Local Themes, click Open Themes Folder.

Place the theme file inside the folder.

The recommended filename is:

KingCordGx.theme.css

Return to Discord and enable KingCordGx.

If the theme does not appear, click Load Missing Themes or reload Discord with:

Ctrl + R

Vencord supports the standard BetterDiscord-compatible .theme.css format.

Option 2 — Online Theme URL

Vencord can load KingCordGx directly from a hosted CSS file, so you do not need to manually download the theme.

Open Discord.

Go to:User Settings → Vencord → Themes

Find Online Themes.

Copy the direct/raw URL to the KingCordGx CSS file.

Paste the URL into the Online Themes field.

The theme should apply automatically.

If necessary, reload Discord with:

Ctrl + R

[!IMPORTANT]The URL must point directly to the CSS file. Do not use the normal GitHub file-view page.

A generic online theme URL looks like:

https://example.com/KingCordGx.theme.css

For files hosted on GitHub, use the corresponding raw.githubusercontent.com URL or another URL that returns the raw CSS directly.

📥 BetterDiscord Installation

Local Theme File

Download the KingCordGx theme file.

Open Discord.

Go to:User Settings → BetterDiscord → Themes

Click Open Themes Folder.

Place the theme file inside the folder.

BetterDiscord theme files should use the following filename format:

KingCordGx.theme.css

Return to Themes and enable KingCordGx.

[!NOTE]BetterDiscord themes require the .theme.css filename format and valid BetterDiscord metadata in addition to the theme's CSS.

You can also browse themes from the official BetterDiscord theme catalog, download them, move them into the Themes folder, and enable them from Discord.

Using an Online-Hosted Theme

Unlike Vencord's Online Themes feature, BetterDiscord normally installs themes as local .theme.css files.

However, a local BetterDiscord theme can import remotely hosted CSS using @import:

@import url("https://example.com/KingCordGx.css");

This allows the local .theme.css loader to retrieve the main stylesheet from an online source.

[!TIP]Using a small local loader with a remote @import makes updating the main stylesheet easier because changes to the hosted CSS can be picked up without manually replacing the entire theme file.

📁 Project Structure

KingCordGx/
├── assets/
│   ├── kingcord-background.jpg
│   └── kingcord-discord-logo.jpeg
│
├── src/
│   └── KingCordGx.css
│
├── dist/
│   └── KingCordGx.theme.css
│
├── LICENSE
└── README.md

File

Description

src/KingCordGx.css

KingCordGx configuration and upstream theme import

dist/KingCordGx.theme.css

Installable Vencord/BetterDiscord theme loader

assets/kingcord-background.jpg

Purple liquid theme background

assets/kingcord-discord-logo.jpeg

Custom Discord Home icon

LICENSE

MIT license for KingCordGx repository content

🔧 How It Works

KingCordGx separates its custom configuration from the upstream theme engine.

KingCordGx
     │
     ├── Custom colors
     ├── Background artwork
     ├── Custom Home icon
     ├── Typography
     └── Theme configuration
              │
              ▼
       OperaGXTheme
              │
              ▼
           Discord

This keeps KingCordGx's branding and configuration maintainable while still benefiting from improvements to the upstream OperaGXTheme project.

🙏 Attribution

The base theme engine is provided by L-Ratio/OperaGXTheme.

KingCordGx contains the custom configuration, branding, assets, and installation setup maintained by xM4j0rPr0bleZx.

Please support and credit the upstream project where appropriate.

📜 License

KingCordGx repository content is released under the MIT License.

The upstream OperaGXTheme dependency remains subject to its own license and terms.

<p align="center">
  <strong>KingCordGx</strong><br>
  Opera GX aesthetics for Discord.
</p>
