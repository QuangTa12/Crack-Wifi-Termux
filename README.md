# Crack Wifi 

![Logo](assets/image.png)

### Scan và check pass wifi thông qua termux (Root).

Lưu ý : Tool này nhằm mục đích giáo dục, thử nghiệm. Tuyệt đối không sử dụng vào các mục đích vi phạm Pháp luật, tôi sẽ không chịu trách nhiệm về hậu quả mà bạn gây ra.
    
- [Yêu cầu]
  - [Python](https://www.python.org)
  - [Pixiewps](https://www.kali.org/tools/pixiewps/)
  - [Wpa-supplicant](https://wiki.archlinux.org/title/wpa_supplicant)
 
### Cài đặt :

```bash
pkg update && pkg upgrade -y
pkg install root-repo -y
pkg install git tsu python wpa-supplicant pixiewps iw openssl -y
git clone https://github.com/QuangTa12/Crack-Wifi-Termux.git
cd Crack-Wifi-Termux
chmod +x lth.py
```
# Nhập thủ công và lưu ý:
(Termux hỏi Y/N, chọn Y)

```bash
pkg update && pkg upgrade -y
```
```bash
pkg install root-repo -y
```
```bash
pkg install git tsu python wpa-supplicant pixiewps iw openssl -y
```
```bash
git clone https://github.com/QuangTa12/Crack-Wifi-Termux.git
```
```bash
cd Crack-Wifi-1
```
```bash
chmod +x lth.py
```

#### lệnh xóa file  :
```bash
cd
```
```bash
sudo rm -rf Crack-Wifi-Termux
```
# Lệnh sử dụng
```bash
cd Crack-Wifi-Termux
```
```bash
sudo python lth.py -i wlan0 -K
```

```bash
bash lth.sh
```
#### Ghi chú :
• Tắt mạng, tắt điểm truy cập, bật vị trí

• Màu xanh là tỉ lệ 60-80% thành công với router đã căn chỉnh wps

• Màu đỏ là ~10%

• Màu trắng là <50%

• Màu vàng là 50%
