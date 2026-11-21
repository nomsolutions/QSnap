# QSnap

**Quick Snap Windows** – Chụp vùng màn hình vào clipboard chỉ với một phím tắt.

[![Release](https://img.shields.io/github/v/release/nomsolutions/QSnap?label=Phiên%20bản)](https://github.com/nomsolutions/QSnap/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/nomsolutions/QSnap/total?label=Lượt%20tải)](https://github.com/nomsolutions/QSnap/releases)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?logo=windows)
![Free](https://img.shields.io/badge/Giá-Miễn%20phí-2ea44f)

<img width="457" height="569" alt="Ảnh cài đặt" src="https://github.com/user-attachments/assets/edd7975d-6303-4ed2-a1dc-29418a5b5748" />

## Tính năng

- **Chụp nhanh bằng phím tắt** – mặc định `Ctrl + Shift + X`, đổi được trong Cài đặt.
- **Kéo chọn vùng** trên toàn bộ màn hình, hiện kích thước vùng chọn theo pixel.
- **Ảnh vào thẳng clipboard** – chụp xong nhấn `Ctrl + V` để dán vào Zalo, Word, email, trình chỉnh ảnh…
- **Xem trước ảnh vừa chụp** trong thông báo góc màn hình (bật/tắt trong Cài đặt).
- **Nhiều màn hình, DPI cao** – chụp đúng pixel thật trên mọi màn hình (Per-Monitor DPI).
- **Gọn nhẹ** – một tệp `.exe` duy nhất, không cần cài .NET, chạy dưới khay hệ thống.
- **Giao diện sáng/tối** tự động theo Windows.
- **Tự cập nhật** – kiểm tra phiên bản mới mỗi ngày, bấm *Cập nhật ngay* là tự tải, kiểm tra mã SHA-256 và cài.

## Cài đặt

1. Tải **`QSnap.exe`** tại trang [Releases](https://github.com/nomsolutions/QSnap/releases/latest).
2. Chạy tệp vừa tải. QSnap tự cài cho người dùng hiện tại (không cần quyền quản trị):
   - Ứng dụng: `%LocalAppData%\Programs\NOM Solutions\QSnap`
   - Có shortcut trong **Start Menu**, mục gỡ cài đặt trong **Settings → Apps**.
   - Mặc định **khởi động cùng Windows** (tắt được trong Cài đặt).
3. Tệp vừa tải có thể xoá sau khi cài.

> **Windows cảnh báo "Windows protected your PC"?** Ứng dụng miễn phí, chưa ký số nên SmartScreen có thể cảnh báo ở lần chạy đầu. Bấm **More info → Run anyway**. Mã SHA-256 của tệp được GitHub hiển thị cạnh tệp đính kèm trong trang Releases để đối chiếu.

**Chạy không cài (portable):** `QSnap.exe --portable`, ví dụ khi chạy từ USB.

## Cách dùng

| Thao tác | Cách làm |
|---|---|
| Chụp vùng màn hình | Nhấn `Ctrl + Shift + X`, hoặc bấm biểu tượng QSnap ở khay hệ thống |
| Chọn vùng | Kéo chuột trái |
| Huỷ | `Esc` hoặc chuột phải |
| Dán ảnh | `Ctrl + V` vào ứng dụng bất kỳ |
| Cài đặt, Giới thiệu | Chuột phải biểu tượng ở khay hệ thống |

> Phím tắt là phím toàn cục, áp dụng cho mọi ứng dụng. Nếu trùng với phím quen dùng (ví dụ `Ctrl + Shift + X` mở Extensions trong VS Code), hãy đổi trong **Cài đặt → Phím tắt chụp vùng màn hình**.

## Cập nhật

- Tự kiểm tra phiên bản mới mỗi ngày (tắt được trong Cài đặt), hoặc vào **Giới thiệu → Kiểm tra cập nhật**.
- Có bản mới: bấm **Cập nhật ngay**, QSnap tự tải, kiểm tra và khởi động lại bản mới. Cài đặt của bạn được giữ nguyên.

## Gỡ cài đặt

**Settings → Apps → QSnap → Uninstall.** Ứng dụng, shortcut, mục khởi động cùng Windows và cấu hình đều được xoá sạch.

## Yêu cầu

- Windows 10 hoặc Windows 11, 64-bit.
- Không cần cài .NET Runtime.

## Thông tin

- Tác giả: **NHTU** – [nhtuid@gmail.com](mailto:nhtuid@gmail.com)
- Phát triển: **Công ty TNHH NOM Solutions**
- Xây dựng bằng thư viện giao diện Nom.Win32 (.NET 10, Native AOT).

© NOM Solutions. Phần mềm miễn phí.
