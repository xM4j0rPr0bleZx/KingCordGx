# KingCordGx

An Opera GX-inspired Discord theme configuration for **Vencord** and **BetterDiscord**, customized and maintained by [xM4j0rPr0bleZx](https://github.com/xM4j0rPr0bleZx).

KingCordGx uses a dark translucent layout, purple accents, a custom background, and the Chakra Petch font. It builds on the upstream [OperaGXTheme](https://github.com/L-Ratio/OperaGXTheme) stylesheet while keeping this project's configuration and install links under the KingCordGx repository.

## Install

### Vencord

1. Open **Settings → Vencord → Themes**.
2. Enable **Online Themes** if needed.
3. Add this URL:

```text
https://xm4j0rpr0blezx.github.io/KingCordGx/dist/KingCordGx.theme.css
```

Alternatively, download [`dist/KingCordGx.theme.css`](https://github.com/xM4j0rPr0bleZx/KingCordGx/raw/main/dist/KingCordGx.theme.css) and place it in your Vencord themes folder.

### BetterDiscord

1. Download [`KingCordGx.theme.css`](https://github.com/xM4j0rPr0bleZx/KingCordGx/raw/main/dist/KingCordGx.theme.css).
2. Open **Discord Settings → BetterDiscord → Themes**.
3. Choose **Open Themes Folder**, move the file there, and enable it.

## GitHub Pages

Open **Settings → Pages**, select **Deploy from a branch**, then choose **main** and **/(root)**. After deployment, the hosted theme URL above will work.

## Customize

Edit the variables in [`src/KingCordGx.css`](src/KingCordGx.css) to change the background, purple accent colors, transparency, blur, fonts, and status colors. Installed copies load the hosted source through `dist/KingCordGx.theme.css`.

## Project structure

- `src/KingCordGx.css` — KingCordGx settings and upstream theme import
- `dist/KingCordGx.theme.css` — installable Vencord/BetterDiscord loader
- `assets/` — screenshots, banners, and other media

## Attribution

The base theme engine is provided by [L-Ratio/OperaGXTheme](https://github.com/L-Ratio/OperaGXTheme). 
KingCordGx contains the configuration and branding maintained by xM4j0rPr0bleZx.

## License

KingCordGx repository content is released under the [MIT License](LICENSE). The upstream dependency remains subject to its own license.
