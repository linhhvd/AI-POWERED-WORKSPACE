# AI-powered Workspace Website

Trang tĩnh “under construction”. Không backend, không build step.

## Chạy

Mở `index.html` trực tiếp, hoặc phục vụ thư mục gốc bằng static server.

Repo: https://github.com/linhhvd/AI-POWERED-WORKSPACE
Pages: https://linhhvd.github.io/AI-POWERED-WORKSPACE/ (nhánh `main`, thư mục gốc)
Tên miền: `aiworkspace.io.vn` — file `CNAME`. DNS tại Mat Bao (`ns1.matbao.vn`, `ns2.matbao.vn`). Apex dùng 4 bản ghi A tới IP GitHub Pages, không CNAME ở `@`.

## Cấu trúc

- `index.html` — markup: tên trang + dòng under construction
- `styles.css` — layout full-viewport, mobile-first

## Quyết định

- Hai dòng nội dung: tên “AI-powered workspace”, rồi “Under construction”
- CSS tách file; font hệ thống, không CDN
- Viewport `100dvh`, `clamp()` cho chữ, `safe-area` cho mobile
