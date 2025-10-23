---
title: "Java Cơ Bản #1: Giới Thiệu Về Java và Cài Đặt Môi Trường"
subtitle: "Giới thiệu về ngôn ngữ lập trình Java, tại sao nên học và hướng dẫn cài đặt môi trường phát triển."
date: 2024-01-20
description: "Giới thiệu về ngôn ngữ lập trình Java, tại sao nên học và hướng dẫn cài đặt môi trường phát triển."
tags: ["java", "cài đặt", "môi trường", "cơ bản", "Java Cơ Bản"]
categories: ["Java"]
bigimg:
- src: "/PersonalBlog/img/hexagon.jpg"
  desc: "Hexagon"
---

## Java là gì?

Java là một ngôn ngữ lập trình hướng đối tượng được phát triển bởi Sun Microsystems (hiện thuộc Oracle) vào năm 1995. Java nổi tiếng với slogan **"Write Once, Run Anywhere"** (Viết một lần, chạy mọi nơi).

### Tại sao nên học Java?

1. **Phổ biến**: Java là một trong những ngôn ngữ được sử dụng nhiều nhất thế giới
2. **Đa nền tảng**: Code Java có thể chạy trên Windows, Mac, Linux
3. **Cộng đồng lớn**: Có rất nhiều tài liệu và hỗ trợ từ cộng đồng
4. **Cơ hội việc làm**: Nhiều công ty tuyển dụng lập trình viên Java

## Cài đặt môi trường Java

### Bước 1: Tải và cài đặt JDK

**JDK** (Java Development Kit) là bộ công cụ phát triển Java.

1. Truy cập trang web chính thức của Oracle: https://www.oracle.com/java/technologies/downloads/
2. Chọn phiên bản JDK mới nhất (khuyến nghị JDK 17 hoặc 21)
3. Tải file cài đặt phù hợp với hệ điều hành của bạn
4. Chạy file cài đặt và làm theo hướng dẫn

### Bước 2: Kiểm tra cài đặt

Mở Command Prompt (Windows) hoặc Terminal (Mac/Linux) và gõ:

```bash
java -version
```

Nếu thấy thông tin phiên bản Java hiển thị, bạn đã cài đặt thành công!

### Bước 3: Cài đặt IDE (Môi trường phát triển)

IDE giúp bạn viết code dễ dàng hơn. Tôi khuyến nghị:

#### IntelliJ IDEA Community (Miễn phí)
1. Truy cập: https://www.jetbrains.com/idea/download/
2. Tải phiên bản Community (miễn phí)
3. Cài đặt và khởi động

#### Eclipse (Miễn phí)
1. Truy cập: https://www.eclipse.org/downloads/
2. Tải Eclipse IDE for Java Developers
3. Giải nén và chạy

## Chương trình Java đầu tiên

Hãy tạo chương trình "Hello World" đầu tiên:

### Bước 1: Tạo file Java

Tạo file mới tên `HelloWorld.java`:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Xin chào, đây là chương trình Java đầu tiên của tôi!");
    }
}
```

### Bước 2: Giải thích code

- `public class HelloWorld`: Khai báo một class công khai tên HelloWorld
- `public static void main(String[] args)`: Phương thức main - điểm bắt đầu của chương trình
- `System.out.println()`: In ra màn hình và xuống dòng

### Bước 3: Biên dịch và chạy

```bash
# Biên dịch
javac HelloWorld.java

# Chạy
java HelloWorld
```

Kết quả:
```
Xin chào, đây là chương trình Java đầu tiên của tôi!
```
