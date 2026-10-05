# A67LG2 Bootsplash

Systemlessly adding Wickedness into your boot logo.

A KernelSU Next module for the **Foxxd A67L Gen 2**. Gen 1 version: [A67LG1-Bootsplash](https://github.com/thewickedlabs/A67LG1-Bootsplash).

Replaces the power-on logo, the boot animation and the boot sound.

## Requirements

- Foxxd A67L Gen 2
- Rooted with KernelSU Next

The installer stops without changing anything if either is missing.

## Install

1. Download `A67LG2-Bootsplash.zip` from Releases.
2. KernelSU Next → Modules → Install from storage → select the zip.
3. Reboot.

## Uninstall

Remove the module in KernelSU Next and reboot.

The boot animation and sound are systemless. The power-on logo isn't: the bootloader reads it straight
from the `logo` and `fbootlogo` partitions. So the installer backs up the originals to
`/data/adb/wickedlabs/bootsplash/` before writing, and uninstalling writes them back.

## License

[WTFPL](LICENSE).

---

Wicked Labs · https://www.cyberspace7.org
