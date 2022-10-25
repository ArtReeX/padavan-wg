```sh
### WireGuard
mkdir /tmp/wireguard
wget https://raw.githubusercontent.com/ArtReeX/padavan-wg/blob/main/client.sh -O /tmp/wireguard/client.sh
wget https://raw.githubusercontent.com/padavan-wg/blob/main/wg0.conf -O /tmp/wireguard/wg0.conf
chmod +x /tmp/wireguard/client.sh
chmod +x /tmp/wireguard/wg0.conf
/tmp/wireguard/client.sh start
```
