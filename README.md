# QR Code Generator

A single-page, browser-based QR code generator. Paste a link (or build Wi‑Fi, email, phone, SMS or contact codes), style it, and download it as PNG, SVG or JPEG at any resolution. Everything runs client-side — nothing you enter leaves your browser.

## Features

- **Content types:** Link/URL (auto-adds `https://`), plain text, Wi‑Fi login, email, phone, SMS, vCard contact
- **Styles:** 6 dot shapes, separate corner square and corner centre shapes, 8 one-click presets
- **Colours:** foreground/background pickers, swap, transparent background, linear/radial gradients, custom corner colour
- **Logo:** upload a centre image with size and padding controls (error correction auto-raised to High)
- **Export:** PNG, SVG, JPEG at 256–4096 px or any custom size (64–8192 px), copy to clipboard, print
- **Scan checks:** warnings for low contrast, inverted colours, small quiet zone and very dense codes
- **History:** recently downloaded codes and your last settings are saved in your browser (localStorage)
- Dark mode and mobile-friendly layout
- Keyboard shortcut: <kbd>Ctrl</kbd>/<kbd>⌘</kbd>+<kbd>S</kbd> downloads the PNG

## Usage

Open `index.html` in any modern browser. No build step or server required.

To host it, enable **GitHub Pages** for the repository (Settings → Pages → deploy from the `main` branch, root folder) and the page will be served at `https://<user>.github.io/<repo>/`.

## Dependencies

- [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) 1.6.0-rc.1, loaded from the jsDelivr CDN (an internet connection is needed on first load).

## License

MIT — see [LICENSE](LICENSE).
