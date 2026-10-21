# 🎱 TonBida

Phần mềm quản lý quán và cửa hàng bi-a chạy trên Windows: tính giờ theo bàn, bán đồ uống và đồ ăn vặt, thu tiền nhanh, báo cáo cho chủ quán.

[⬇️ Tải bản mới nhất](https://github.com/manhbui0811/TonBida/releases/latest/download/TonBida.exe) · [Tất cả phiên bản](https://github.com/manhbui0811/TonBida/releases) · [Trang giới thiệu](https://manhbui0811.github.io/TonSoft/#TonBida)

## Tính năng
- Sơ đồ bàn: mở bàn, tạm dừng, chuyển bàn, sửa giờ, kết thúc và tính tiền
- Tính giờ tự động theo loại bàn và khung giờ, có làm tròn phút và mức tối thiểu
- Combo giờ chơi kèm nước tặng
- Gọi đồ uống, đồ ăn vặt ngay trên bàn đang chơi, hoặc bán lẻ không cần bàn
- Thu tiền mặt hoặc chuyển khoản, mã VietQR hiện sẵn đúng số tiền
- In hóa đơn có tên bàn và dòng tiền giờ chơi
- Khuyến mãi áp được cả vào tiền giờ chơi, tích điểm khách quen
- Kho, nhập hàng, nhà cung cấp, kiểm kho
- Sổ thu chi, Dashboard doanh thu theo bàn, khung giờ, nhân viên, xuất Excel
- Tài khoản nhân viên và chủ quán, phân quyền tiền bạc, sao lưu và khôi phục dữ liệu

## Yêu cầu
- Windows 10 hoặc 11, 64-bit
- RAM từ 4 GB, trống khoảng 500 MB ổ cứng
- Microsoft Edge WebView2 Runtime (Windows 11 và hầu hết Windows 10 đã có sẵn; nếu máy báo thiếu, tải tại https://developer.microsoft.com/microsoft-edge/webview2/)

## Cách dùng
TonBida là một file `.exe` duy nhất, không cần cài .NET.
1. Tải file `TonBida.exe`.
2. Đặt file vào một thư mục riêng, ví dụ `C:\TonBida\`.
3. Mở file. Nếu Windows báo chặn, chọn **Thông tin thêm → Vẫn chạy**.
4. Lần đầu mở, tạo tài khoản quản trị ở màn hình **Chào mừng**. Bạn có thể nạp sẵn danh mục, sản phẩm, bàn và bảng giá mẫu cho quán bi-a rồi chỉnh lại cho đúng quán của mình.

## Dữ liệu của bạn
- Dữ liệu lưu trong file `app.db` được tạo ngay **cạnh file exe**. Nếu thư mục chứa exe không ghi được, dữ liệu nằm ở `%APPDATA%\TonBida`.
- Vì vậy hãy đặt exe trong thư mục riêng và không đặt ở nơi bị khóa ghi như `C:\Program Files`.
- Nâng cấp phiên bản mới: thoát phần mềm, chép file exe mới đè lên file cũ trong cùng thư mục, giữ nguyên `app.db`.
- Nên dùng chức năng **sao lưu** trong phần mềm và chép bản sao lưu ra ổ khác thường xuyên.

## Kiểm tra file tải về
Mã SHA256 nằm trong phần mô tả của mỗi bản phát hành. Kiểm tra bằng PowerShell:

```
certutil -hashfile TonBida.exe SHA256
```

## Báo lỗi và góp ý
Mở tab **Issues** của repo này, mô tả lỗi và đính kèm ảnh chụp màn hình.

## Liên hệ
Zalo / điện thoại: 09740413209 · Email: manhbui0811@gmail.com
