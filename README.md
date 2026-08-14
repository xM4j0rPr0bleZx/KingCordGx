# KingCordGx

A regal black-and-gold Discord theme for **Vencord** and **BetterDiscord**, maintained by [xM4j0rPr0bleZx](https://github.com/xM4j0rPr0bleZx).

## Preview

KingCordGx gives Discord a deep charcoal surface, warm gold accents, softened panels, and clear interactive states while keeping the familiar Discord layout.

## Install

### Vencord

1. Open **Settings → Vencord → Themes**.
2. Enable **Online Themes** if needed.
3. Add this URL:

```text
https://xm4j0rpr0blezx.github.io/KingCordGx/dist/KingCordGx.theme.css
```

You can also download [`dist/KingCordGx.theme.css`](https://github.com/xM4j0rPr0bleZx/KingCordGx/raw/main/dist/KingCordGx.theme.css) and place it in your Vencord themes folder.

### BetterDiscord

1. Download [`KingCordGx.theme.css`](https://github.com/xM4j0rPr0bleZx/KingCordGx/raw/main/dist/KingCordGx.theme.css).
2. Open **Discord Settings → BetterDiscord → Themes**.
3. Choose **Open Themes Folder**, move the file there, and enable it.

## GitHub Pages

In this repository, open **Settings → Pages**, select **Deploy from a branch**, then choose **main** and **/(root)**. Once Pages finishes deploying, the hosted theme URL above will work.

## Customize

Edit the variables near the top of [`src/KingCordGx.css`](src/KingCordGx.css). The file in `dist/` is the loader users install; it imports the hosted source so updates are delivered automatically.

## Project structure

- `src/KingCordGx.css` — theme source and customization variables
- `dist/KingCordGx.theme.css` — installable BetterDiscord/Vencord loader
- `assets/` — screenshots, banners, and other media

## Notes

Discord class names can change. If an update breaks part of the theme, open an issue with a screenshot and a short description.

## License

Released under the [MIT License](LICENSE).
