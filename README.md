# My Scripts

This a set of scripts working thought *dmenu*.

To run it starts the selector menu using the `dmenu_menu` script. It is suggested to add that script to a shortcut.

Implemented scripts:

- `bw`, an interface to [Bitwarden](https://bitwarden.com/) it required `bw` command
- `redshift`, an interface to [RedShift](http://jonls.dk/redshift/) it required `redshift` command
- `windscribe`, an interface to [Windscribe](https://windscribe.com/) VPN it required `windscribe`, command
- `surfshark`, an interface to [Surfshark](https://surfshark.com/) VPN it required `surfshark-vpn` command

## Installation

First of all, make sure to have installed *dmenu* on your OS.

Then download the repository and add it in your `$PATH`.
For instance, add the following line to your `.bashrc` file.

```
export PATH="$PATH:$HOME/myscripts"
```

Configure a new shortcut to your desktop environment to the `$HOME/myscripts/dmenu_menu` (e.g., `Super+r`).

## License
MIT License

credit to *Tom Vincent* for the `dmenu_menu` script.
