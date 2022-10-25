```sh
### WireGuard
[ -d /etc/storage/wireguard ] || mkdir /etc/storage/wireguard
wget https://raw.githubusercontent.com/ArtReeX/padavan-wg/main/client.sh -O /etc/storage/wireguard/client.sh
wget https://raw.githubusercontent.com/ArtReeX/padavan-wg/main/wg0.conf -O /etc/storage/wireguard/wg0.conf
chmod +x /etc/storage/wireguard/client.sh
chmod +x /etc/storage/wireguard/wg0.conf
/etc/storage/wireguard/client.sh start
```
