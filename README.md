
```console
/etc/storage/wireguard/client.sh autostart
```

```sh
### WireGuard
mkdir /etc/storage/wireguard >/dev/null 2>&1
wget https://raw.githubusercontent.com/ArtReeX/padavan-wg/main/client.sh -O /etc/storage/wireguard/client.sh >/dev/null 2>&1
wget https://raw.githubusercontent.com/ArtReeX/padavan-wg/main/wg0.conf -O /etc/storage/wireguard/wg0.conf >/dev/null 2>&1
chmod +x /etc/storage/wireguard/client.sh >/dev/null 2>&1
chmod +x /etc/storage/wireguard/wg0.conf >/dev/null 2>&1

```
