# QR Local

**QR Local** is a free, local-first QR code generator distributed as a single HTML file. It runs entirely in the browser, works offline, requires no account, and does not send QR content or usage data to a server.

> Made by Kriss.

## Try it online

**Live app:** https://krisosom.github.io/qr-local/

**Source code:** https://github.com/KrisOsoM/qr-local

The hosted version is provided for convenience. QR generation, imported files, and usage statistics are still processed locally in the browser; no QR payload or telemetry is intentionally sent to the author.

## Why QR Local exists

Many QR services are account-based, cloud-dependent, or reserve useful features for subscription plans. QR Local focuses on static QR creation that the user can keep and run locally with no recurring fee, no registration, and no external service dependency.

## Features

- Single-file application: `index.html`
- Works offline after download
- No account or installation required
- Static QR codes for:
  - URL
  - Text
  - Wi-Fi
  - WhatsApp
  - Phone
  - Email
  - vCard
- PNG and vector SVG export
- Custom foreground/background colors with contrast guidance
- Optional center logo with high error correction
- Batch generation from CSV and XLSX
- Configurable file naming and sequential numbering
- ZIP export with PNG/SVG folders and `manifest.csv`
- Local-only usage statistics
- Statistics by QR type and by day
- Local activity charts
- CSV export of local statistics

## Privacy

QR Local is designed to work locally:

- QR contents are processed in the browser.
- Imported CSV/XLSX files are processed locally.
- The application makes no intentional network requests.
- No telemetry is sent to the author.
- Local statistics contain counters and dates only; they do not store QR payloads.

See [PRIVACY.md](PRIVACY.md) for details.

## How to use

1. Download `index.html`.
2. Optionally rename it to `QR Local.html`.
3. Open it with a modern browser.
4. Choose a QR type and enter the content.
5. Generate and export as PNG or SVG.

For batch generation, open the **Generación masiva** tab and load a CSV or XLSX file.

## Platforms

Because QR Local is a self-contained browser application, it can run on modern browsers on:

- macOS
- Windows
- Linux
- Web/browser environments that allow local HTML execution

Mobile browsers may work, but mobile distribution is not currently a tested/release target.

## Current release

**v2.6.1**

See [CHANGELOG.md](CHANGELOG.md).

## Open-source license

QR Local is released under the **MIT License**. Copyright © 2026 Kriss. See [LICENSE](LICENSE).

Third-party components retain their own licenses. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Security

See [SECURITY.md](SECURITY.md).

## Author

**Kriss** — “Made by Kriss”