<h1 align="center">
  <a href="https://github.com/SonzaiEkkusu/scriptvps"><img src="https://github.com/SonzaiEkkusu/scriptvps/raw/master/assets/logo.png" alt="LOGO"></a>
</h1>

### PERHATIAN
- Terima kasih untuk tidak menjual maupun mengenkripsi skrip ini. Saya mendapatkan secara gratis, jadi saya ataupun kalian harus berbagi secara gratis.
- Script ini **tidak direkomendasikan untuk bermain game**.
- Status servis terkadang miss informasi. Dimana pada status dead tetapi jika dilihat by servis statusnya sudah aktif. Jadi bisa diabaikan
- Jika mendapatkan error pada status servis dalam jangka panjang, bisa restart servis yang dead.

### INSTALL SCRIPT
<pre><code>apt install -y wget screen && wget -q https://raw.githubusercontent.com/SonzaiEkkusu/scriptvps/master/main.sh && chmod +x main.sh && screen -S install ./main.sh</code></pre>


### TESTED ON OS 
- UBUNTU 20.04.05

### FITUR TAMBAHAN
- Tambah Swap 1GiB
- Pemasangan yang dinamis
- Tuning profile pada server
- Xray Core by [@dharak36](https://github.com/dharak36/Xray-core)
- Penambahan fail2ban
- Penggunaan [Tiarap](https://github.com/pengelana/blocklist) sebagai dns resolver.

### PORT INFO
```
    ┌─────────────────────────────────────────────────────┐
    │       >>> Service & Port                            │
    │   - OpenSSH                 : 22                    │
    │   - DNS (SLOWDNS)           : 443, 80, 53           │
    │   - Dropbear                : 39, 109, 143          │
    │   - SSH Websocket SSL       : 443                   │
    │   - SSH Websocket           : 80 (UNTEST)           │
    │   - OpenVPN SSL             : 443, 1194 (UNTEST)    │
    │   - OpenVPN Websocket SSL   : 443 (UNTEST)          │
    │   - OpenVPN TCP             : 1194 (UNTEST)         │
    │   - OpenVPN UDP             : 2200 (UNTEST)         │
    │   - Nginx Webserver         : 81                    │
    │   - DNS Server              : 443, 53               │
    │   - DNS Client              : 443, 88               │
    │   - XRAY DNS (SLOWDNS)      : 443, 80, 53           │
    │   - XRAY Vmess TLS          : 443                   │
    │   - XRAY Vmess gRPC         : 443                   │
    │   - XRAY Vmess None TLS     : 80                    │
    │   - XRAY Vless TLS          : 443                   │
    │   - XRAY Vless gRPC         : 443                   │
    │   - XRAY Vless None TLS     : 80                    │
    │   - Trojan gRPC             : 443                   │
    │   - Trojan WS               : 443                   │
    │   - Shadowsocks WS          : 443                   │
    │   - Shadowsocks gRPC        : 443                   │
    └─────────────────────────────────────────────────────┘

```

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```
### STATUS
`Beta Testing`

### Lisensi
Repository ini dilindungi oleh lisensi [MIT](https://mit-license.org/)

### Credits
- [Dharak36](https://github.com/dharak36/Xray-core)
- [Tiarap](https://github.com/pengelana/blocklist)