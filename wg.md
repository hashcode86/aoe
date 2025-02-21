# WireGuard Client
* Tải & cài đặt [client](https://download.wireguard.com/windows-client/wireguard-installer.exe) 

# WireGuard Config
* Mở app WireGuard, Chọn **Add empty tunnel**
  ![1](https://github.com/user-attachments/assets/d66d580d-a924-4d6a-8a4c-599b9d36d049)

* Nhập các thông tin cấu hình, ví dụ:
  ![2](https://github.com/user-attachments/assets/a60fe9cc-1fbd-4d34-b3ba-6b5bff7e2041)

  * Name: AOE
  * Body: theo mẫu dưới
  * Public key: Tự sinh, không phải nhập

* Bấm **Save**, sau đó chọn **Active/Deactive** để kết nối hoặc ngắt kết nối

```Properties
[Interface]
Address = IP_LẤY_TỪ_BẢN DƯỚI
PrivateKey = KEY_ỨNG_VỚI_IP_ĐÃ_CHỌN
ListenPort = 51820

[Peer]
PublicKey = klg5oQTQ90iBYGbwYKcTC3ZddYWbTQSS2vaddDcytD0=
AllowedIPs = 10.10.10.0/24
Endpoint = aoe-wg.io.vn:51820
PersistentKeepalive = 25

[Peer]
PublicKey = cYbNgvsGBhjls9rK62DDUgK2xGg830O65ltuaJyGnDg=
AllowedIPs = 10.10.10.2/32
Endpoint = hashcode.tplinkdns.com:51820
PersistentKeepalive = 25
```

| IP         | Key                                          | Đã dùng    |
| ---------- | -------------------------------------------- | ---------- |
| 10.10.10.3 | 8GG0tcfUd4Tp8BZ7A6SGm6PdEANopOqiWi51cjSOcUA= | XienXien   |
| 10.10.10.4 | CP+b0jD6TPpx7q4VNuKgTx684M0dF8V21PmLjN0Ja2k= | JT         |
| 10.10.10.5 | yGgyDphyyNfZ+NY0mxS5Sd6Vlqa03mpFoWsNPyfv0XI= | M3P        |
| 10.10.10.6 | eDNosNi6J+bUO5MbnilvlIpAHbO4Zo0waY7Lw4Uhf1Q= | RO         |
| 10.10.10.7 | uEocqMztc+HOkn2zmCS8PSdFT7NML8HYgToyWLzbSUk= | JAMES      |
| 10.10.10.8 | sJiSK6qTdKJMqZGg7Fno3q6K3mOlgul+Yf154LeKq1o= | Thuyết     |
| 10.10.10.9 | iGACsQG/1U3x7yEDOgirGdC4XSGrukFKDEvc3wk50k8= | Khá        |

# AOE trong thư mục của EGO, ví dụ:
* D:\softwares\EGOPlay\Game\AOE1: bản thường
* D:\softwares\EGOPlay\Game\AOEFULL: bản HD
