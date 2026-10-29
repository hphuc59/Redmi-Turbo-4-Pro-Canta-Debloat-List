
# Redmi Turbo 4 Pro — Canta Debloat List

A device-specific debloat list for the **Redmi Turbo 4 Pro**, designed for use with [Canta](https://github.com/samolego/Canta).

The goal is to help users identify and remove unwanted pre-installed apps while preserving essential system functionality.

## Features

- 📱 Designed for Redmi Turbo 4 Pro
- 🧹 Helps remove unwanted pre-installed apps
- 🔧 Intended for use with Canta
- 🛡️ Focus on system stability and essential functionality
- 🤝 Open to community feedback and contributions

## Requirements

- Redmi Turbo 4 Pro
- Android / HyperOS version compatible with the listed packages
- [Canta](https://github.com/samolego/Canta)
- [Shizuku](https://shizuku.rikka.app/) to provide the required permissions

## Usage

1. Back up important data before making changes.
2. Install and configure Shizuku.
3. Install Canta and grant the required permissions.
4. Review the package list in `config.txt`.
5. Check each app's purpose before removing it.
6. Remove only the apps you understand and do not need.
7. Restart your device and verify that essential features still work.

**Important:** Do not blindly remove every package in the list. Package behavior may vary across HyperOS versions and regions.

## Repository Structure

```text
.
├── README.md
└── config.txt
```

- `config.txt` — Debloat configuration for reference and use with the intended workflow.

## Compatibility

| Item | Details |
|---|---|
| Device | Redmi Turbo 4 Pro |
| Operating system | HyperOS; exact version to be verified |
| Debloat tool | Canta |
| Root required | No, when using the Shizuku method |

Compatibility and package behavior may differ depending on the ROM, region, and software version.

## Safety & Disclaimer

- This project is provided for educational and informational purposes.
- Removing system packages may affect notifications, updates, connectivity, or other device features.
- Back up important data before debloating.
- Keep a record of removed packages so you can restore them if necessary.
- The author is not responsible for issues caused by package removal.
- This list is not an official Xiaomi or Redmi product.

## Contributions

Found an issue or have a suggestion?

Feel free to open an issue or submit a pull request. Include your device's HyperOS version and the package name when reporting a problem.

## License

A license has not yet been specified. Please add a `LICENSE` file before defining reuse and distribution permissions.
