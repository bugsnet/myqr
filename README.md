# myqr
## QR Code scanner for login hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```
<button onclick="window.location='https://bugsnet.github.io/myqr';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="Mikhmon QR Code Scanner" disabled=no dst-host=bugsnet.github.io
```

### Powered by webqr.com / laksa19.github.io
