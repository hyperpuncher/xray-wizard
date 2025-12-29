## Install

```sh
curl -sOL https://github.com/hyperpuncher/xray-wizard/raw/refs/heads/main/xray-wizard
chmod +x xray-wizard
mv xray-wizard /usr/local/bin
```

## Usage

```sh
Usage: xray-wizard [options]

Options:
	-a, --add <client_name>    Add new client
	-r, --remove <client_name> Remove client
	-l, --list                 List clients
	-g, --get <client_name>    Get client config
	-i, --init                 Setup xray
	-u, --update               Update script
	    --uninstall            Uninstall script
```

## Apps

### Linux

#### Arch

```sh
sudo paru -S xray
```

### Windows

```sh
winget install --id=MatsuriDayo.NekoRay -e
```

### macOS

```sh
brew install xray
```

### Android

[v2rayNG](https://github.com/2dust/v2rayNG)

### iOS

[Streisand](https://apps.apple.com/app/streisand/id6450534064)
