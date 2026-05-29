# 🍬 Bubblegum

**Sweet & Secure Password Generator for Linux Mint**

Bubblegum generates strong, random passwords for Linux Mint using PyQt5.

## Features

- Password length from 8 to 64 characters
- Uppercase letters (A-Z)
- Lowercase letters (a-z)
- Numbers (0-9)
- Symbols (!@#$%^&*)
- Exclude ambiguous characters (il1Lo0O)
- One-click copy to clipboard
- Real-time password strength indicator
- Native .deb package

## Installation

Download bubblegum.deb from Releases.

Install with:

sudo dpkg -i bubblegum.deb
sudo apt install -f

## Launch

From terminal: bubblegum

From application menu: Search for "Bubblegum"

## Uninstall

sudo dpkg -r bubblegum

## Dependencies

Installed automatically:
- python3-pyqt5
- python3-pyqt5.qtsvg
- xclip

## License

MIT
