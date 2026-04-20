# Mẫu Báo Cáo LaTeX (HCMUS Style)

[![LaTeX](https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)](https://github.com/F0n9/LaTeX-Report-Template/graphs/commit-activity)
[![HCMUS](https://img.shields.io/badge/HCMUS-VNU--HCM-blue?style=for-the-badge)](https://hcmus.edu.vn/)

Template báo cáo LaTeX chuyên nghiệp, sạch sẽ và có cấu trúc module, thiết kế phù hợp cho sinh viên **Đại học Khoa học Tự nhiên - ĐHQG TP.HCM**.

## ✨ Các tính năng nổi bật
- **Cấu trúc Module**: Tách biệt phần cấu hình (style) và nội dung (content), giúp dễ dàng quản lý và tái sử dụng cho nhiều môn học khác nhau.
- **Hỗ trợ Tiếng Việt tốt**: Sử dụng bảng mã T5 và gói `vietnam` truyền thống, đảm bảo hiển thị đúng mọi ký tự tiếng Việt.
- **Tùy biến cao**: Dễ dàng thay đổi thông tin cá nhân, logo trường và các mục lục tự động.

## 📂 Cấu trúc thư mục
- `main.tex`: File thực thi chính. Bạn sẽ biên dịch file này.
- `style/`: Chứa các file định dạng:
  - `config.tex`: Nơi nạp các gói lệnh (packages) và thiết lập font.
  - `cover_page.tex`: Mẫu trang bìa chuyên nghiệp (Đã có sẵn thông tin mẫu).
  - `header_footer.tex`: Định dạng đầu trang và chân trang.
  - `logo.png`: Logo trường (có thể thay thế).
- `chapter/`: Chứa nội dung báo cáo:
  - `content.tex`: Viết nội dung chính của báo cáo tại đây.
- `assets/`: Thư mục để chứa hình ảnh minh họa cho báo cáo.
- `ref.bib`: File chứa các tài liệu tham khảo (BibLaTeX).

## 🚀 Hướng dẫn sử dụng
1.  **Môi trường**: Bạn nên cài đặt **MiKTeX** (Windows) và VS Code (với extension LaTeX Workshop).
2.  **Biên dịch**: 
    - Sử dụng trình biên dịch **pdfLaTeX**.
    - Nên biên dịch 2 lần để cập nhật đúng số trang trong Mục lục.
3.  **Tùy chỉnh**:
    - Vào `style/cover_page.tex` để sửa tên môn học, đề tài và thông tin giảng viên.
    - Vào `chapter/content.tex` để bắt đầu viết nội dung.

## 📄 LICENSE
Dự án này được phát hành dưới giấy phép **MIT License**, cho phép bạn tự do sử dụng và sửa đổi cho mục đích học tập.

---
*From aoe1920 with ❤️*
