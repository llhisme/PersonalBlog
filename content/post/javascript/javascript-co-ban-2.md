---
title: "JavaScript Cơ Bản #2: Biến, Kiểu Dữ Liệu và Toán Tử"
subtitle: "Tìm hiểu chi tiết về biến, các kiểu dữ liệu và toán tử trong JavaScript"
date: 2024-02-01
description: "Tìm hiểu chi tiết về biến, các kiểu dữ liệu và toán tử trong JavaScript"
tags: ["javascript", "biến", "kiểu dữ liệu", "toán tử", "cơ bản", "JavaScript Cơ Bản"]
categories: ["JavaScript"]
bigimg:
- src: "/PersonalBlog/img/hexagon.jpg"
---

## Biến trong JavaScript

**Biến** (Variable) là nơi lưu trữ dữ liệu trong chương trình. JavaScript có 3 cách khai báo biến: `var`, `let`, và `const`.

### 1. Cách khai báo biến

```javascript
// var - cách cũ (không khuyến nghị)
var ten = "JavaScript";

// let - biến có thể thay đổi (khuyến nghị)
let tuoi = 25;

// const - hằng số (không thể thay đổi)
const PI = 3.14159;

console.log(ten, tuoi, PI);
```

## Kiểu dữ liệu trong JavaScript

JavaScript có 2 nhóm kiểu dữ liệu chính:

### 1. Primitive Types (Kiểu nguyên thủy)

- **Number**: Số nguyên và số thực
- **String**: Chuỗi ký tự
- **Boolean**: `true` hoặc `false`
- **Undefined**: Biến đã được khai báo nhưng chưa được gán giá trị
- **Null**: Biểu thị giá trị rỗng hoặc không tồn tại
- **Symbol**: Giá trị duy nhất và bất biến

### 2. Non-Primitive Types (Kiểu tham chiếu)

- **Object**: Đối tượng
- **Array**: Mảng

## Toán tử trong JavaScript

### 1. Toán tử số học

- `+` (Cộng), `-` (Trừ), `*` (Nhân), `/` (Chia), `%` (Chia lấy dư), `**` (Lũy thừa)

### 2. Toán tử gán

- `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `**=`

### 3. Toán tử so sánh

- `==` (Bằng), `!=` (Khác), `===` (Bằng nghiêm ngặt), `!==` (Khác nghiêm ngặt), `>`, `<`, `>=`, `<=`

### 4. Toán tử logic

- `&&` (VÀ), `||` (HOẶC), `!` (PHỦ ĐỊNH)
