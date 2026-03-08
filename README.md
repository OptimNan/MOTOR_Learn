# MOTOR_Learn
电机学习仓库

## 扫一扫 / QR Code Scanner

本仓库包含一个基于浏览器的二维码扫描页面（扫一扫）。

This repository includes a browser-based QR code scanner (扫一扫).

### 打开方法 / How to Open

直接在浏览器中打开 `scan.html` 文件，或将其托管到 Web 服务器后访问。

Open `scan.html` directly in your browser, or host it on any web server and navigate to it.

#### 功能 / Features

- **摄像头扫描** — 点击"开始扫描"按钮，授权摄像头后自动扫描二维码。  
  Click **开始扫描 / Start** to scan a QR code using your device camera.
- **图片上传** — 点击"上传图片"按钮，从相册或文件中选取含二维码的图片进行解码。  
  Click **上传图片 / Upload** to decode a QR code from an image file.
- **链接直达** — 扫描结果如为 URL，可直接点击打开。  
  If the result is a URL, a clickable link is shown.

#### 使用要求 / Requirements

- 现代浏览器（Chrome、Firefox、Edge、Safari）。  
  A modern browser (Chrome, Firefox, Edge, Safari).
- 摄像头功能需在 HTTPS 或 localhost 下使用。  
  Camera access requires HTTPS or localhost.
- 无需安装任何依赖，QR 解码库通过 CDN 自动加载。  
  No installation needed; the jsQR decoding library loads via CDN.
