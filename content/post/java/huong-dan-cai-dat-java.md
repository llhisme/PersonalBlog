---
title: "Hướng dẫn cài đặt Java trên Windows"
date: 2025-10-28
categories: ["Java"]
tags: ["java", "installation", "tutorial"]
_build:
  list: false
  render: true
bigimg:
- src: "/PersonalBlog/img/sphere.jpg"
---

# Hướng dẫn cài đặt Java trên Windows

Trong bài viết này, tôi sẽ hướng dẫn các bạn cách cài đặt Java trên hệ điều hành Windows.

## Các bước cài đặt

### 1. Chạy file cài đặt

- Double-click vào file `.exe` đã tải về (thường có tên dạng `jdk-[version]_windows-x64_bin.exe`)
- Nếu có thông báo bảo mật từ Windows, click "Yes" để cho phép chương trình chạy
- Click "Next" để bắt đầu quá trình cài đặt

### 2. Chọn thư mục cài đặt

- Mặc định, Java sẽ được cài đặt vào thư mục `C:\Program Files\Java\jdk-[version]`
- Bạn có thể thay đổi đường dẫn nếu muốn, nhưng khuyến nghị giữ nguyên đường dẫn mặc định
- Click "Next" để tiếp tục

### 3. Chờ quá trình cài đặt hoàn tất

- Quá trình này sẽ mất vài phút
- Đợi cho đến khi thấy thông báo "Setup Completed"
- Click "Close" để kết thúc

### 4. Thiết lập biến môi trường

1. **Thiết lập JAVA_HOME**
   - Mở Start Menu, gõ "Environment Variables" và chọn "Edit the system environment variables"
   - Click vào nút "Environment Variables"
   - Trong phần "System variables", click "New"
   - Variable name: `JAVA_HOME`
   - Variable value: Đường dẫn đến thư mục cài đặt JDK (ví dụ: `C:\Program Files\Java\jdk-17`)
   - Click "OK"

2. **Cập nhật Path**
   - Trong phần "System variables", tìm biến "Path"
   - Click "Edit"
   - Click "New"
   - Thêm `%JAVA_HOME%\bin`
   - Click "OK" để lưu tất cả thay đổi

### 5. Kiểm tra cài đặt

1. Mở Command Prompt (cmd)
2. Gõ lệnh sau để kiểm tra phiên bản Java:
```bash
java --version
```
3. Nếu thấy thông tin về phiên bản Java, nghĩa là bạn đã cài đặt thành công

## Xử lý sự cố thường gặp

1. **Lỗi "java is not recognized as an internal or external command"**
   - Kiểm tra lại biến môi trường Path
   - Đảm bảo đường dẫn trong JAVA_HOME chính xác
   - Thử restart máy tính

2. **Không thể mở file cài đặt**
   - Đảm bảo bạn đã tải đúng phiên bản cho Windows
   - Thử chạy file với quyền Administrator
   - Kiểm tra phần mềm antivirus có đang chặn không

## Kết luận

Sau khi hoàn thành các bước trên, bạn đã có thể bắt đầu lập trình Java trên máy tính của mình. Đừng quên cài đặt một IDE (Integrated Development Environment) như Eclipse, IntelliJ IDEA hoặc Visual Studio Code để có môi trường lập trình thuận tiện hơn.

Chúc các bạn thành công!