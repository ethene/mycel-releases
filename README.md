# Mycel Releases

[![Latest Release](https://img.shields.io/github/v/release/ethene/mycel-releases?label=version)](https://github.com/ethene/mycel-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/ethene/mycel-releases/total)](https://github.com/ethene/mycel-releases/releases)
[![Get it on Obtainium](https://img.shields.io/badge/Obtainium-Get%20Mycel-green)](https://apps.obtainium.imranr.dev/redirect.html?r=obtainium://add/https://github.com/ethene/mycel-releases)

**Mycel** is a delay-tolerant mesh messenger for Android. Messages hop between phones using Bluetooth and Wi-Fi Direct - no internet required.

## Install

### Obtainium (Recommended)

[![Get it on Obtainium](https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png)](https://apps.obtainium.imranr.dev/redirect.html?r=obtainium://add/https://github.com/ethene/mycel-releases)

1. Install [Obtainium](https://github.com/ImranR98/Obtainium) from [F-Droid](https://f-droid.org/packages/dev.imranr.obtainium.fdroid/) or [GitHub](https://github.com/ImranR98/Obtainium/releases)
2. **Click the badge above** to add Mycel automatically
3. Or manually add this URL: `https://github.com/ethene/mycel-releases`
4. Obtainium will notify you of updates and verify signatures automatically

> **Connection error?** If Obtainium can't connect to GitHub, check your internet connection, try a different network (some block GitHub), or temporarily disable VPN/ad blockers. [Full troubleshooting guide](https://ethene.github.io/mycel-docs/reference/faq/#cannot-add-mycel-source-from-github-obtainium)

### Manual Download

1. Go to [Releases](https://github.com/ethene/mycel-releases/releases)
2. Download `Mycel-vX.X.X.apk`
3. Enable "Install from unknown sources" in Android settings
4. Install the APK

## Verify Your Download

Each release includes a SHA-256 checksum file. [Full verification guide](https://ethene.github.io/mycel-docs/security/verification/)

**Official Certificate Fingerprint:**
```
SHA-256: 446a854ca21ef946e1ae192a685cde06a791d4ae8e9eb3844a9ef537fa688d6d
```

Quick verification:
```bash
# Linux/macOS
sha256sum Mycel-v*.apk
cat Mycel-v*.apk.sha256

# If you have Android SDK
apksigner verify --print-certs Mycel-v*.apk
```

## Features

- **Works offline** - No internet required, uses Bluetooth & Wi-Fi Direct
- **No phone number** - Identified by cryptographic key
- **End-to-end encrypted** - Only recipient can read messages
- **No servers** - Fully peer-to-peer mesh network
- **Open source** - Transparency you can verify

## Requirements

- Android 8.0+ (API 26)
- Bluetooth & Location permissions (for mesh discovery)

## Documentation

Full documentation at **[ethene.github.io/mycel-docs](https://ethene.github.io/mycel-docs)**

- [Getting Started](https://ethene.github.io/mycel-docs/getting-started/install/)
- [How It Works](https://ethene.github.io/mycel-docs/how-it-works/overview/)
- [Privacy](https://ethene.github.io/mycel-docs/security/privacy/)
- [FAQ](https://ethene.github.io/mycel-docs/reference/faq/)

## Release Files

Each release contains:

| File | Description |
|------|-------------|
| `Mycel-vX.X.X.apk` | The app |
| `Mycel-vX.X.X.apk.sha256` | SHA-256 checksum |
| `mapping.txt` | ProGuard mapping for crash reports |

## Security

- APKs are signed with a consistent release key
- Certificate fingerprint published above and in [docs](https://ethene.github.io/mycel-docs/security/verification/)
- Open source - [audit the code](https://github.com/ethene/mycel) (private, contact for access)

## Support

- [Documentation](https://ethene.github.io/mycel-docs)
- [Report Issues](https://github.com/ethene/mycel-releases/issues)

## License

Mycel is open source software.
