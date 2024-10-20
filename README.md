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

Bypass URL : 
```rsc
/ip hotspot walled-garden ip
add action=accept disabled=no dst-host=desktop.niceradius.com;
add action=accept disabled=no dst-host=duitku.com;
```
FUTUR TERSEDIA :
- Login Mode Voucher
- Login Mode Member
- Payment Gateway
- Riwayat Transaksi
- Auto Clear Active Session
- Gambar Slide


PILIHAN WARNA
- 0 = amber
- 1 = black
- 2 = red
- 3 = blue-grey
- 4 = blue
- 5 = cyan
- 6 = dark-grey
- 7 = deep-orange
- 8 = deep-purple
- 9 = green
- 10 = indigo
- 11 = light-blue
- 12 = light-green
- 13 = lime
- 14 = orange
- 15 = pink
- 16 = purple
- 17 = teal
- 18 = yellow
