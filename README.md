### ENABLE

```sh
mkdir /etc/storage/wireguard
wget https://raw.githubusercontent.com/ArtReeX/padavan-wg/main/client.sh -O /etc/storage/wireguard/client.sh
wget https://raw.githubusercontent.com/ArtReeX/padavan-wg/main/wg0.conf -O /etc/storage/wireguard/wg0.conf
chmod +x /etc/storage/wireguard/client.sh
chmod +x /etc/storage/wireguard/wg0.conf
/etc/storage/wireguard/client.sh start
ping -c 3 -W 1 1.1.1.1
/etc/storage/wireguard/client.sh stop
/etc/storage/wireguard/client.sh autostart enable
mtd_storage.sh save
```

### DISABLE

```sh
/etc/storage/wireguard/client.sh stop
/etc/storage/wireguard/client.sh autostart disable
rm -rf /etc/storage/wireguard
mtd_storage.sh save
```
