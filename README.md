# CDS – Quản lý Cư Dân Số · Bản cài trên máy tính

Phần mềm quản lý địa bàn dân cư cho thôn, bản, tổ dân phố, xã, phường. Bản này
chạy trên **một máy tính Windows**, dữ liệu nằm trên chính máy đó, **không cần
mạng**, **miễn phí**.

## Tải về

**[⬇ Tải bộ cài CDS cho Windows](https://github.com/Trustydev212/CDS-ban-cai/releases/latest/download/CDS-cai-dat.exe)** (khoảng 110 MB)

Đường dẫn trên luôn trỏ tới bản mới nhất. Các bản cũ xem ở mục
[Releases](https://github.com/Trustydev212/CDS-ban-cai/releases).

Cần: Windows 10 hoặc 11, bản 64-bit.

## Cài đặt

1. Mở tệp `CDS-cai-dat.exe` vừa tải.
2. Nếu Windows hiện màn hình xanh **"Windows protected your PC"**: bấm
   **More info** → **Run anyway**. Cảnh báo này hiện vì bộ cài chưa có chữ ký số
   của hãng, không phải do phần mềm có hại.
3. Chọn thư mục cài (để mặc định là được), bấm **Install**.
4. Mở CDS từ biểu tượng trên màn hình hoặc menu Start.

## Lần đầu mở

- Vào **Cài đặt → Đơn vị**, chọn loại đơn vị (thôn, bản, tổ dân phố, xã,
  phường…) và gõ tên. Tên này in trên đầu tệp Excel và chỗ ký giấy xác nhận.
- Nhập dữ liệu: gõ tay từng hộ, hoặc **Nhập từ Excel** nếu đã có sổ trên Excel.
- Muốn xem thử trước: **Cài đặt → Vùng nguy hiểm → Nạp 60 hộ dữ liệu mẫu**. Đây
  là dữ liệu giả, xóa đi trước khi nhập dữ liệu thật.

## Giữ dữ liệu an toàn

Dữ liệu chỉ nằm trên máy này. Máy hỏng, mất máy hay cài lại Windows là **mất
dữ liệu**, trừ khi đã sao lưu.

- Vào **Sao lưu** thường xuyên, chép tệp sao lưu ra USB hoặc máy khác. Trang chủ
  sẽ nhắc khi đã lâu chưa sao lưu.
- Nên đặt **mã mở khóa** (Cài đặt → Khóa ứng dụng) và mật khẩu Windows: dữ liệu
  dân cư là dữ liệu cá nhân.
- Cài bản mới đè lên bản cũ **không mất dữ liệu**. Gỡ cài đặt cũng không xóa dữ
  liệu (nằm ở `%APPDATA%\CDS`).

## Nhiều người cùng làm?

Bản này dùng trên một máy. Khi cần nhiều cán bộ cùng nhập, hoặc xã xem tổng
hợp nhiều thôn, có thể **nâng cấp lên bản online** (máy chủ đặt tại Việt Nam):
vào **Cài đặt → Nâng cấp lên bản online**. Dữ liệu đang có được đưa lên, không
phải nhập lại. Liên hệ người cung cấp phần mềm để được cấp máy chủ.

## Giới hạn

- Quét mã QR căn cước bằng camera chưa dùng được trên Windows; phần mềm tự
  chuyển sang nhập tay.
- Nền bản đồ cần có mạng; mất mạng thì vị trí các hộ và nút dẫn đường vẫn dùng
  được.
- Phần mềm không tự cập nhật: tải bộ cài mới ở đường dẫn trên và cài đè.
