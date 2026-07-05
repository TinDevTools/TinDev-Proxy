# TINDEV x PROXY SCRAPER

Tool tự đồng crawl và check proxy đa luồng, hỗ trợ nhiều nguồn và giao thức `HTTP` • `HTTPS` • `SOCKS4` • `SOCKS5`. Viết bằng Python, sử dụng module `aiohttp` để cho tốc độ cao và giao diện đẹp mắt với module `tkinter` + `webview`.

## Features

• **Crawl** nguồn proxy từ github thông qua **Github Token**.<br>
• **Check Proxy** với tốc độ cao hỗ trợ đa luồng.<br>
• **Giao diện chuyên nghiệp** sử dụng `Html` làm giao diện và module `webview` để hiển thị<br>
• **Cấu hình linh hoạt** có thể tuỳ chỉnh một hoặc nhiều giao thức.<br>
• **Lưu kết quả** có thể tuỳ chỉnh giao thức lưu sau khi `Check Proxy`.<br>
• **Hỗ trợ cài module** tool tự động cài module cần thiết.

## Requirements

• Python 3.12+<br>
• Các thư viện: 
```bash
pip install pywebview customtkinter aiohttp requests ujson PySocks
