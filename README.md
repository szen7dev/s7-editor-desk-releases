# S7 Editor — bộ cài Windows

Phần mềm **S7 Editor** của [Szen7](https://szen7.com): dựng video module Editor của S7 bằng cấu hình máy bàn của bạn
(tải clip về máy, dựng bằng mọi nhân CPU, mất mạng vẫn dựng, có mạng lại tự đẩy video lên S7).

**Tải bản mới nhất:** [Releases → Latest](https://github.com/szen7dev/s7-editor-desk-releases/releases/latest) → tệp `S7-Editor-Setup-<phiên bản>.exe`.
Cài xong, đăng nhập bằng tài khoản S7 có quyền **Dựng video** (Editor video). Phần mềm tự cập nhật từ trang này.

Repo này chỉ chứa bộ cài và tệp đi kèm theo giấy phép — mã nguồn phần mềm S7 Editor không công khai.

## Giấy phép phần mềm bên thứ ba

Bộ cài kèm **FFmpeg** (bản dựng gyan.dev "full_build", không sửa đổi) theo **GNU GPL phiên bản 3**; S7 Editor gọi FFmpeg như
chương trình riêng. Mỗi bản phát hành đính kèm:

- `ffmpeg-<phiên bản>.tar.xz` — mã nguồn FFmpeg đúng phiên bản (từ ffmpeg.org);
- `ffmpeg-buildconf.txt` — cấu hình dựng chính xác của bản FFmpeg đi kèm.

Mã nguồn các thư viện bên thứ ba trong bản dựng FFmpeg (libx264, …) được cung cấp theo yêu cầu trong ít nhất 3 năm — xem
`THIRD-PARTY-NOTICES.txt` (cũng nằm trong thư mục cài đặt, mục khay **Giới thiệu & giấy phép**). Liên hệ: https://szen7.com/#tu-van
