# HỆ THỐNG CHƠI FRUIT NINJA BẰNG CỬ CHỈ TAY 🍉🖐️

Dự án xây dựng hệ thống điều khiển game Fruit Ninja thông qua nhận diện cử chỉ tay (Hand Gestures) bằng Camera, sử dụng Python và OpenCV.

## Mục tiêu & Yêu cầu
* Xây dựng hệ thống phát hiện va chạm, tính điểm với giao diện đơn giản.
* Chạy ổn định trên Windows.
* Điều khiển chuột máy tính bằng ngón tay và click chuột bằng cử chỉ.

## Công nghệ & Môi trường
* **Ngôn ngữ:** Python 3.10 (Khuyến nghị bản 3.10.10 hoặc 3.10.11 để tương thích tốt nhất).
* **Thư viện chính:** OpenCV, Mediapipe, Cvzone, Numpy, PyAutoGUI, Mouse.
* **Môi trường:** Virtualenv (khuyên dùng).

---

## Hướng dẫn Cài đặt

### Bước 1: Cài đặt Python
* Yêu cầu phiên bản Python 3.10.X.

* Bạn có thể khám khảo link cài đặt: https://www.youtube.com/watch?v=yZFG5ktaZtU, sau khi cài xong chúng ta có thể thức hiện viết code ngay.

### Bước 2: Tạo và kích hoạt môi trường ảo
Mở Terminal (CMD hoặc PowerShell) tại thư mục dự án:
#### 1. Tạo môi trường ảo:
```bash
python -m venv venv
```
#### 2. Kích hoạt môi trường:

```bash
venv\Scripts\activate

```
(Sau khi kích hoạt, đầu dòng lệnh sẽ có chữ (venv)).
### Bước 3: Cài đặt thư viện

```bash
pip install opencv-contrib-python cvzone mouse pyautogui
```

## 🎮 Hướng dẫn chạy chương trình

### Bước 1: Chạy Code
Trong Terminal (đang kích hoạt venv), chạy lệnh:

```bash 
python fruit_ninja_ges.py
```

### Bước 2: Chơi Game

Sau khi Camera hiện lên, dùng tay di chuyển để điều khiển chuột. Truy cập các link sau để chơi:

* **Coolmath Games:** https://www.coolmathgames.com/0-fruit-ninja