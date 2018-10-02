# mac shortcut services

Services to open and resize windows.

## Services

### [Open Chrome](/services/open_chrome.workflow/Contents)

![](https://raw.githubusercontent.com/dunckr/mac-shortcut-services/master/assets/open_chrome.gif)

## Why?

If you have a locked down machine (no admin access) and you wish to navigate between applications and resize quickly.

If you have admin access to your machine I highly recommend either [Phoenix](https://github.com/kasper/phoenix) or [Spectacle](https://www.spectacleapp.com/).

Due to mac permissions these applications require administrative privileges to setup accessibility access. We can install services using applescript to accomplish similar basic functionality.

## Install

1. Install the services

* All:

```sh
bash <(curl -s https://raw.githubusercontent.com/dunckr/mac-shortcut-services/master/install.sh)
```

* Individually

Clone the repo:

```sh
git clone git@github.com:dunckr/mac-shortcut.services.git
```

Open the services you require under the `services` folder

2. Refresh Services

```sh
Any Application Toolbar -> Menu -> Services -> Service Preferences...
```

3. Setup Shortcuts

```sh
System Preferences -> Keyboard -> Shortcuts -> Services -> Installed Services at the bottom of the list
```

## License

MIT © [Duncan Beaton](https://dunckr.com)
