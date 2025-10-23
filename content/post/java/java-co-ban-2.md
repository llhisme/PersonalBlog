---
title: "Java Cơ Bản #2: Biến và Kiểu Dữ Liệu"
subtitle: "Tìm hiểu về biến và các kiểu dữ liệu cơ bản trong Java với ví dụ thực tế"
date: 2024-01-22
description: "Tìm hiểu về biến và các kiểu dữ liệu cơ bản trong Java với ví dụ thực tế"
tags: ["java", "biến", "kiểu dữ liệu", "cơ bản", "Java Cơ Bản"]
categories: ["Java"]
bigimg:
- src: "/PersonalBlog/img/sphere.jpg"
---

## Biến là gì?

**Biến** (Variable) là một "hộp" để lưu trữ dữ liệu trong chương trình. Mỗi biến có một tên và một kiểu dữ liệu cụ thể.

Ví dụ đơn giản:
```java
int tuoi = 25;        // Biến lưu số tuổi
String ten = "Nam";   // Biến lưu tên
```

## Cách khai báo biến

### Cú pháp cơ bản:
```java
kieuDuLieu tenBien = giaTriKhoiTao;
```

## Các kiểu dữ liệu cơ bản

### 1. Kiểu số nguyên

| Kiểu | Kích thước | Phạm vi | Ví dụ |
|------|------------|---------|-------|
| `byte` | 1 byte | -128 đến 127 | `byte tuoi = 25;` |
| `short` | 2 byte | -32,768 đến 32,767 | `short nam = 2024;` |
| `int` | 4 byte | -2 tỷ đến 2 tỷ | `int luong = 15000000;` |
| `long` | 8 byte | Rất lớn | `long danSo = 97000000L;` |

### 2. Kiểu số thực

| Kiểu | Kích thước | Độ chính xác | Ví dụ |
|------|------------|--------------|-------|
| `float` | 4 byte | 7 chữ số | `float diem = 8.5f;` |
| `double` | 8 byte | 15 chữ số | `double pi = 3.14159;` |

### 3. Kiểu ký tự và chuỗi

- `char`: Lưu một ký tự duy nhất, ví dụ: `char kyTu = 'A';`
- `String`: Lưu một chuỗi ký tự, ví dụ: `String ten = "Java";`

### 4. Kiểu logic

- `boolean`: Chỉ có hai giá trị `true` hoặc `false`, ví dụ: `boolean daKetHon = false;`
