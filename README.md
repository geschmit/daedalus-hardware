# Daedalus EDA Files
These are the KiCAD EDA files for Hack Club Cafe's "Daedalus" mystery prize. 
- Pico 2 Form Factor: Identical pinouts, flash size, onboard LED, etc...
- Peripherals: Includes a 6x4 LED matrix, USB-C male connector, and broken-out USB and SWD lines for easy hacking
- Keychainability: Put it on your keyring with a slotted hole on the end!

Latest revision (C) is what was given out to Cafe grant recepients. Prototype revisions A and B are also provided, but it is advised **not to use them** as they contain manufacturing errors and have been left as-is for archival purposes.

Should run the Micro/CircuitPython builds for Pico 2 without a sweat, along with any Pico 2 targetted code.

## LED Matrix Pinout

| Row/Col | GPIO Pin |
|---------|----------|
| Row 0   | GPIO12   |
| Row 1   | GPIO13   |
| Row 2   | GPIO14   |
| Row 3   | GPIO15   |
| Col 0   | GPIO17   |
| Col 1   | GPIO18   |
| Col 2   | GPIO19   |
| Col 3   | GPIO20   |
| Col 4   | GPIO21   |
| Col 5   | GPIO22   |

## Licensing
Daedalus is shared under two license agreements; only one will apply. Please see each for more information.
- Hack Club Staff & active employees: Daedalus License Agreement. Please contact either me, Acon or current acting Cafe project representative for more information.
- Everybody else: [CC BY-NC-SA 4.0](./LICENSE)
