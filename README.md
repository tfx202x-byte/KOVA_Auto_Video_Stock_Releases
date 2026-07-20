# KOVA Auto Video Stock — Client Releases

Repo công khai này chỉ dùng để phân phối các bản build cho client. Mã nguồn được lưu trong repo private riêng.

## Tải bản mới nhất

Mở mục [Releases](https://github.com/tfx202x-byte/KOVA_Auto_Video_Stock_Releases/releases/latest), sau đó tải file:

`KOVA-Auto-Video-Stock-<version>-Windows-x64.exe`

Ứng dụng là bản portable dành cho Windows x64, đã tích hợp FFmpeg và FFprobe nên không cần cài riêng.

## Kiểm tra file tải về

Mỗi bản phát hành có file `.sha256`. Trên PowerShell, chạy:

```powershell
Get-FileHash .\KOVA-Auto-Video-Stock-2.0.0-Windows-x64.exe -Algorithm SHA256
```

Đối chiếu kết quả với nội dung file `.sha256` trong cùng bản phát hành.
