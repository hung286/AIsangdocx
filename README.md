# Chuyển đổi AI sang DOCX & Add-in Word MH 2026 (Bản Độc Lập)

Thư mục dự án độc lập gồm công cụ **Chuyển đổi AI sang DOCX** (dán văn bản từ ChatGPT, Gemini, Claude... xuất file Word `.docx` có bảng và công thức toán OMML / MathType) và bộ **Add-in Word MH 2026**.

## Cấu trúc thư mục
- `index.html`: Trang chính, có sẵn nút tải Add-in Word MH 2026 ở thanh tiêu đề.
- `app.js`, `PasteAiPage.css`: Mã nguồn công cụ Chuyển đổi AI sang DOCX (chạy trực tiếp trên trình duyệt, không cần build).
- `assets/`: `jszip.min.js`, `katex.min.css`, `katex.min.js` (có kèm CDN fallback).
- `addin/`: Bộ cài đặt Add-in Word MH 2026 (`Cai_Dat_Addin_Word_MH2026.exe`, `MH2026.dotm`, `Cap_Nhat_Addin_Vao_Word.bat`, `Tronde.bas`, `VBA_Pro_Backup.dotm`).

## Triển khai
Đưa toàn bộ thư mục này lên GitHub / Vercel / Netlify / GitHub Pages hoặc chạy local bằng `npx serve .`.
