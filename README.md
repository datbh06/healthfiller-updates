# HealthFiller — cấu hình cập nhật

`form-map.hfu` là cấu hình form website CSDLKSK đã **ký số** bằng khóa của nhà cung cấp.
Phần mềm HealthFiller (bản 1.1.9 trở lên) tự tải file này và chỉ dùng khi chữ ký hợp lệ và phiên bản mới hơn.

- Không chứa mã nguồn, khóa bí mật hay dữ liệu học sinh — chỉ có vị trí các ô trên form.
- Không sửa tay: file được tạo bằng `LicenseTool publish-map`; sửa tay làm hỏng chữ ký và phần mềm sẽ bỏ qua.
