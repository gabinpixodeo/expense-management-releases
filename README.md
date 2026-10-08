# Sổ Chi Tiêu — bản phát hành Android

Bản APK mới nhất được mô tả trong [`latest.json`](latest.json); ứng dụng đọc tệp này
khi khởi động (và khi bấm **Cài đặt → Kiểm tra cập nhật**) để đề nghị cập nhật.

## Cài đặt lần đầu

Tải tệp APK ở [bản phát hành mới nhất](../../releases/latest), mở trên điện thoại
Android và cho phép **Cài ứng dụng không rõ nguồn gốc** khi được hỏi.

## `latest.json`

| Trường | Ý nghĩa |
| --- | --- |
| `versionCode` | Số build (phải tăng dần) |
| `versionName` | Tên phiên bản hiển thị |
| `apkUrl` | Link tải APK trong GitHub Releases (https) |
| `sizeBytes` | Dung lượng APK |
| `notes` | Ghi chú thay đổi hiển thị trong ứng dụng |
| `mandatory` | `true` = bắt buộc cập nhật |
| `minVersionCode` | Các bản cũ hơn số này bắt buộc cập nhật |
