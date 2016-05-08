# Ozon Rebooted
This is a fork of the default icon theme for OzonOS, which is now defunct. It also contains several variants with different coloured folders. It's licensed under the GNU GPLv3.

## Installing
Download, [download the source](https://github.com/digitalgutenberg/ozon-rebooted-icon-theme/archive/master.zip), extract it, and copy the "Ozon" folder to one of the following icon theme locations:

* **Global** (all users)
  * `/usr/share/icons/`
* **Local** (current user)
  * `~/.icons`
  * `~/.local/share/icons/`

**You can also run the following commands in your terminal:**
```bash
git clone https://github.com/digitalgutenberg/ozon-rebooted-icon-theme.git
cd ozon-rebooted-icon-theme
make install
```

## Hardcoded Icons
To deal with hardcoded application icons Ozon uses the [hardcode-fixer](https://github.com/Foggalong/hardcode-fixer) script. To deal with hardcoded status icons we recommend you use the [Hardcode Tray](https://github.com/bil-elmoussaoui/Hardcode-Tray) script.
