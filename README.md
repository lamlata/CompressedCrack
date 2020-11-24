# CompressedCrack
Phá mã file rar, zip


## Requirements:
Tải python và cài đặt, link dưới:
[Python 3.x]
(https://www.python.org/downloads/)

Sử dụng
```
Sau khi tải file về, extract ra, vào trong folder mở của sổ CMD trong folder bằng shift + chuột phải => chọn Open Powershell Window here

Bên trong cửa sổ CMD gõ cú pháp: 

python crack.py -i INPUT [rules [rules ...]]

Ví dụ: python crack.py -i D:\boku\ganktem.zip 5 7 axuy69

trong đó 
INPUT đường dẫn tời file
5,7, axuy69: Crack những pass trong khoảng từ 5->7 ký tự và các ký tự thuộc tập hợp (a,x,u,y,6,9)

Nên set ký tự: abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890
Chiều dài thì nên set 6->9 
Nếu pass càng dài sẽ mất nhiều thời gian để crack
