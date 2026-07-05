Cách upload đúng lên GitHub Pages:

1. Copy TOÀN BỘ các mục sau vào root repo linh-999.github.io:
   - index.html
   - assets/
   - writeups/
   - projects/

2. Cấu trúc đúng phải là:
   D:\IO\update\linh-999.github.io\index.html
   D:\IO\update\linh-999.github.io\assets\style.css
   D:\IO\update\linh-999.github.io\writeups\soc-alert-investigation.html
   D:\IO\update\linh-999.github.io\projects\centralized-security-monitoring.html

3. Nếu chỉ có index.html và assets/ thì bấm Write-ups/Projects sẽ bị 404.

4. Push:
   git add .
   git commit -m "fix portfolio navigation"
   git push origin main
