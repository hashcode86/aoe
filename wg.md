# WireGuard Client
* Tải & cài đặt [client](https://download.wireguard.com/windows-client/wireguard-installer.exe) 

# WireGuard Config
* Mở app WireGuard, Chọn **Add empty tunnel**
  ![1](https://github.com/user-attachments/assets/d66d580d-a924-4d6a-8a4c-599b9d36d049)

* Nhập các thông tin cấu hình, ví dụ:
  ![2](https://github.com/user-attachments/assets/a60fe9cc-1fbd-4d34-b3ba-6b5bff7e2041)

  * Name: AOE
  * Public key: Tự sinh
  * Body: theo mẫu dưới

```Properties
[Interface]
Address = IP_LẤY_TỪ_BẢN DƯỚI
PrivateKey = KEY_ỨNG_VỚI_IP_ĐÃ_CHỌN
ListenPort = 51820

[Peer]
PublicKey = klg5oQTQ90iBYGbwYKcTC3ZddYWbTQSS2vaddDcytD0=
AllowedIPs = 10.10.10.0/24
Endpoint = 171.244.63.15:51820
PersistentKeepalive = 25

[Peer]
PublicKey = cYbNgvsGBhjls9rK62DDUgK2xGg830O65ltuaJyGnDg=
AllowedIPs = 10.10.10.2/32
Endpoint = 171.236.87.133:51820
PersistentKeepalive = 25
```

| IP         | Key                                          |
| ---------- | -------------------------------------------- |
| 10.10.10.3 | 8GG0tcfUd4Tp8BZ7A6SGm6PdEANopOqiWi51cjSOcUA= |
| 10.10.10.4 | CP+b0jD6TPpx7q4VNuKgTx684M0dF8V21PmLjN0Ja2k= |
| 10.10.10.5 | yGgyDphyyNfZ+NY0mxS5Sd6Vlqa03mpFoWsNPyfv0XI= |
| 10.10.10.6 | eDNosNi6J+bUO5MbnilvlIpAHbO4Zo0waY7Lw4Uhf1Q= |
| 10.10.10.7 | uEocqMztc+HOkn2zmCS8PSdFT7NML8HYgToyWLzbSUk= |
| 10.10.10.8 | sJiSK6qTdKJMqZGg7Fno3q6K3mOlgul+Yf154LeKq1o= |
| 10.10.10.9 | iGACsQG/1U3x7yEDOgirGdC4XSGrukFKDEvc3wk50k8= |
