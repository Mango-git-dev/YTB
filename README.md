# YTB
- Cày view cho ytb

- Đầu tiên tải [Python](https://www.python.org/downloads/) và [ChromeDriver](https://developer.chrome.com/docs/chromedriver/downloads)
- Sau đó chuyển ChromeDrive vào cùng thư mục với file cày view
- Mở file list_url_video.txt -> gắn link youtube bạn muốn cày view vào
- Mở file luong_xem.txt -> điền số lần hoàn thành (được tính sau khi đóng 1 tab)
- Sau đó mở cmd bằng cách ấn Windows+R
- Tải thư viện selenium,pystyle bằng cách nhập pip install + tên thư viện
- Lúc này đừng vội tắt tab cmd,bạn có thể chạy luôn view.py bằng cách nhập python view.py
- Chọn số tab để mở video (tùy vào cấu hình của máy chọn cho phù hợp tránh lag máy)
- Chọn thời gian xem cho mỗi vdeo (không nên để ít quá khuyến nghị để 30s)
- *** Key : Mango | DeewMango ***
``` Giải thích về nguyên lý:
- Tools tự động mở tab và chạy tất cả các link được đặt trong file list_url_video.txt
- Có thể chọn số tab muốn mở và đặt giới hạn thời gian xem cho mỗi video
