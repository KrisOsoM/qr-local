# Contributing to QR Local

Thank you for your interest in QR Local.

## Project principles

Changes should preserve the core philosophy:

1. **Local first** — QR content stays on the user's device.
2. **No subscription** — core functionality remains usable without recurring payment.
3. **No account requirement** — generating QR codes must not require registration.
4. **Offline capable** — the distributed build should remain usable without Internet access.
5. **Single-file distribution** — the main release should remain easy to download, keep and run.
6. **Privacy by default** — no remote telemetry by default.

## Contributions

Before submitting a change:

- verify QR generation for the affected QR types;
- verify PNG and SVG export;
- verify that batch export still generates valid ZIP and manifest files;
- check that no unintentional external resources or network calls were introduced;
- test the statistics view if the change touches local counters or storage;
- keep third-party license notices intact.

## Issues

Bug reports should include browser/OS, QR Local version, steps to reproduce, expected behavior and actual behavior. Do not include private QR payloads unless they are synthetic test data.