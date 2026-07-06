HƯỚNG DẪN CẬP NHẬT LÊN GITHUB PAGES

1. Giải nén file ZIP.
2. Mở thư mục bên trong, nơi có các file/thư mục:
   - index.html
   - assets/
   - projects/
   - writeups/
3. Copy toàn bộ nội dung đó vào root repo: linh-999.github.io
4. Mở Git Bash trong thư mục repo và chạy:

   git status
   git add .
   git commit -m "Refine personal portfolio content"
   git push origin main

Lưu ý:
- Không copy thư mục .git từ ZIP cũ nếu có.
- GitHub Pages phân biệt chữ hoa/thường trong tên file.
- Sau khi push, mở https://linh-999.github.io và nhấn Ctrl + F5 nếu trang chưa cập nhật ngay.
