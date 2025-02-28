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
| 10.10.10.3  | ******************************************** | XienXien   |
| 10.10.10.4  | ******************************************** | Thuyết     |
| 10.10.10.5  | ******************************************** | M3P        |
| 10.10.10.6  | ******************************************** | RO         |
| 10.10.10.7  | ******************************************** | JT         |
| 10.10.10.8  | ******************************************** | JAMES      |
| 10.10.10.9  | ******************************************** | Khá        |
| 10.10.10.10 | IAQsLAYS19r1SxhfAbs8vYVgw9KPxLrrJi+BDdRCbnA= |            |
| 10.10.10.11 | ePaPMOjbXAzyfXi+5f/6jxRNQOXdl860QBGKy1KlVkc= |            |
| 10.10.10.12 | sD+oRio+C/KZSCbeyogUl/uDQYIR4GxwxqM6sZ2YEmU= |            |
| 10.10.10.13 | UGs/zu0B1pGSvP3L3wFWXkDGhuAM8gaeadlJiQLEo0w= |            |

# AOE trong thư mục của EGO, ví dụ:
* D:\softwares\EGOPlay\Game\AOE1: bản thường
* D:\softwares\EGOPlay\Game\AOEFULL: bản HD
