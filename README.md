# Corne Feather nRF52840 ZMK Config

Configuration ZMK pour un Corne split avec Feather nRF52840 Express.

## Build automatique

Le CI GitHub Actions compile automatiquement les deux fichiers `.uf2` quand tu push sur `main`.

## Hardware

- Feather nRF52840 Express x2
- 24 switches (6x4 par moitié)
- Diodes 1N4148 (col2row)
- Pinout : Rows D4,D5,D6,D9 | Cols A4,A5,A0,A1,A3,A2

## Flash

Déposer le `.uf2` sur le Feather branché en mode bootloader.
