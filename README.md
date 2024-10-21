# LP MikroTik 01

Edit file config.js sebelum digunakan
```js
var config = {
clear_session       : true,
api_url             : 'https://desktop.niceradius.com/api',
api_key             : '',
router_id           : '',
merchant_code       : '',
merchant_api_key    : '',
fonnte_token        : '',
contact             : 'https://wa.me/6281234567890',
currency            : 'Rp',
color               : 17
}
```
| Variable  | Value |
| ------------- | ------------- |
| clear_session | true / false  |
| api_key  | dari https://desktop.niceradius.com |
| router_id  | dari https://desktop.niceradius.com |
| merchant_code | dari https://duitku.com |
| merchant_api_key | dari https://duitku.com |
| fonnte_token | dari https://fonnte.com |
| color  | 0 - 18 |

### (Required) Bypass Server URL : 
```js
/ip hotspot walled-garden ip
add action=accept disabled=no dst-host="desktop.niceradius.com";
add action=accept disabled=no dst-host="duitku.com";
```
### FUTUR TERSEDIA :
- Login Mode Voucher
- Login Mode Member
- Payment Gateway
- Riwayat Transaksi
- Auto Clear Active Session
- Gambar Slide


### PILIHAN WARNA
- ![#ffc107](https://placehold.co/15x15/ffc107/ffc107.png) `0 - Amber`
- ![#000000](https://placehold.co/15x15/000000/000000.png) `1 - Black`
- ![#f44336](https://placehold.co/15x15/f44336/f44336.png) `1 - Red`
- ![#607d8b](https://placehold.co/15x15/607d8b/607d8b.png) `1 - Blue Grey`
- ![#2196f3](https://placehold.co/15x15/2196f3/2196f3.png) `1 - Blue`
- ![#00bcd4](https://placehold.co/15x15/00bcd4/00bcd4.png) `1 - Cyan`
- ![#616161](https://placehold.co/15x15/616161/616161.png) `1 - Dark Grey`
- ![#ff5722](https://placehold.co/15x15/ff5722/ff5722.png) `1 - Deep Orange`
- ![#673ab7](https://placehold.co/15x15/673ab7/673ab7.png) `1 - Deep Purple`
- ![#4caf50](https://placehold.co/15x15/4caf50/4caf50.png) `1 - Green`
- ![#3f51b5](https://placehold.co/15x15/3f51b5/3f51b5.png) `1 - Indigo`
- ![#87ceeb](https://placehold.co/15x15/87ceeb/87ceeb.png) `1 - Light Blue`
- ![#8bc34a](https://placehold.co/15x15/8bc34a/8bc34a.png) `1 - Light Green`
- ![#cddc39](https://placehold.co/15x15/cddc39/cddc39.png) `1 - Lime`
- ![#ff9800](https://placehold.co/15x15/ff9800/ff9800.png) `1 - Orange`
- ![#e91e63](https://placehold.co/15x15/e91e63/e91e63.png) `1 - Pink`
- ![#9c27b0](https://placehold.co/15x15/9c27b0/9c27b0.png) `1 - Purple`
- ![#009688](https://placehold.co/15x15/009688/009688.png) `1 - Teal`
- ![#ffeb3b](https://placehold.co/15x15/ffeb3b/ffeb3b.png) `1 - Yellow`


### (Optional) Bypass Metode Pembayaran DANA :
```js
/ip hotspot walled-garden ip
add action=accept disabled=no comment="DANA" dst-host="m.dana.id";
add action=accept disabled=no comment="DANA" dst-host="dana.id";
add action=accept disabled=no comment="DANA" dst-host="split.io";
add action=accept disabled=no comment="DANA" dst-host="sdk.split.io";
add action=accept disabled=no comment="DANA" dst-host="auth.split.io";
add action=accept disabled=no comment="DANA" dst-host="events.split.io";
add action=accept disabled=no comment="DANA" dst-host="a.m.dana.id";
add action=accept disabled=no comment="DANA" dst-host="mas-log1.saas.dana.id";
add action=accept disabled=no comment="DANA" dst-host="api-js.mixpanel.com";
add action=accept disabled=no comment="DANA" dst-host="captcha.saas.dana.id";
add action=accept disabled=no comment="DANA" dst-host="dana-assets-id.oss-ap-southeast-5.aliyuncs.com";
```
