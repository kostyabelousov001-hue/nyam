# nyam

Release channel for **nyc**, the Wayland shell of a native Arch Linux ARM on the Poco M5s (rosemary).
This repository carries only signed OTA releases (`latest.json`, `latest.json.sig`, `nyc-N.tgz`). The phone checks them under
Settings > Updates; every package is verified with an ed25519 signature before anything is installed.

## What is in the shell
- Home screen with folders, library, search, customisation; quick-settings shade with shortcut tiles
- Keyboard (EN/RU) with clipboard history, edit keys, back / home / recents buttons, long-press for e->yo and digits
- Apps: Phone, Messages, Camera, Gallery, Notes, Files, Calendar (with reminders), Clock, Calculator, Market (pacman / AUR), Settings
- First-run setup (OOBE) with Wi-Fi, SIM, updates and component selection
- Own ringtones, time zone, signed over-the-air updates with rollback
