```ssh
### WireGuard
rm -rf /etc/storage/wireguard
wget https://github.com/ArtReeX/padavan-wg/blob/main/client.sh -O /etc/storage/wireguard/client.sh
wget https://github.com/ArtReeX/padavan-wg/blob/main/wg0.conf -O /etc/storage/wireguard/wg0.conf
chmod +x /etc/storage/wireguard/client.sh
chmod +x /etc/storage/wireguard/wg0.conf
/etc/storage/wireguard/client.sh start
```
