# WireGuard installer

Easily set up a dual-stack [WireGuard](https://www.wireguard.com/) VPN on a Linux server. See the issues for the WIP.

## Requirements

Supported distributions:

- Ubuntu
- Debian
- Fedora
- Centos
- Arch Linux

I recommend these cheap cloud providers for your VPN server:

- [Fozzy](https://go.kontemplado.com/42gnn).
- [HostZealot](https://go.kontemplado.com/58lm1).

## Usage

First, get the script and make it executable :

```bash
curl -O https://raw.githubusercontent.com/kontemplado/wireguard-install/master/wireguard-install.sh
chmod +x wireguard-install.sh
```

Then run it :

```sh
./wireguard-install.sh
```

It will install wireguard on the server, configure, create a systemd service and a client configuration file. Mutliple clients are not yet supported.

Contributions are welcome!
