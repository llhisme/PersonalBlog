---
title: "Java Cơ Bản #5: Vòng Lặp - For, While và Do-While"
subtitle: "Tìm hiểu các loại vòng lặp trong Java và cách sử dụng chúng hiệu quả"
date: 2024-01-28
description: "Tìm hiểu các loại vòng lặp trong Java và cách sử dụng chúng hiệu quả"
tags: ["java", "vòng lặp", "for", "while", "do-while", "cơ bản", "Java Cơ Bản"]
categories: ["Java"]
bigimg:
- src: "/PersonalBlog/img/sphere.jpg"
---

## Vòng lặp là gì?

**Vòng lặp** (Loop) cho phép chúng ta thực hiện một đoạn code nhiều lần mà không cần viết lại. Giống như khi bạn cần in 100 số từ 1 đến 100, thay vì viết 100 dòng `System.out.println()`, bạn chỉ cần dùng vòng lặp.

Java có 3 loại vòng lặp chính:
- **For loop**: Biết trước số lần lặp
- **While loop**: Lặp khi điều kiện còn đúng
- **Do-while loop**: Thực hiện ít nhất 1 lần, sau đó kiểm tra điều kiện

## 1. Vòng lặp For

### Cú pháp cơ bản:
```java
for (khởi_tạo; điều_kiện; cập_nhật) {
    // Code thực hiện trong mỗi lần lặp
}
```

## 2. Vòng lặp While

### Cú pháp:
```java
while (điều_kiện) {
    // Code thực hiện khi điều kiện đúng
    // Cần có code để thay đổi điều kiện, tránh vòng lặp vô hạn
}
```

## 3. Vòng lặp Do-While

### Cú pháp:
```java
do {
    // Code thực hiện ít nhất 1 lần
} while (điều_kiện);
```
