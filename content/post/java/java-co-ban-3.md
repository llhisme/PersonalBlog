---
title: "Java Cơ Bản #3: Toán Tử và Biểu Thức"
subtitle: "Tìm hiểu các loại toán tử trong Java và cách sử dụng chúng trong biểu thức"
date: 2024-01-24
description: "Tìm hiểu các loại toán tử trong Java và cách sử dụng chúng trong biểu thức"
tags: ["java", "toán tử", "biểu thức", "cơ bản", "Java Cơ Bản"]
categories: ["Java"]
bigimg:
- src: "/PersonalBlog/img/hexagon.jpg"
  desc: "Hexagon"
---

## Toán tử là gì?

**Toán tử** (Operator) là các ký hiệu đặc biệt được sử dụng để thực hiện các phép toán trên dữ liệu. **Biểu thức** (Expression) là sự kết hợp của các biến, hằng số và toán tử.

## 1. Toán tử số học (Arithmetic Operators)

| Toán tử | Ý nghĩa | Ví dụ | Kết quả |
|---------|---------|-------|---------|
| `+` | Cộng | `5 + 3` | `8` |
| `-` | Trừ | `5 - 3` | `2` |
| `*` | Nhân | `5 * 3` | `15` |
| `/` | Chia | `10 / 3` | `3` (chia nguyên) |
| `%` | Chia lấy dư | `10 % 3` | `1` |

## 2. Toán tử gán (Assignment Operators)

| Toán tử | Tương đương | Ví dụ |
|---------|-------------|-------|
| `+=` | `a = a + b` | `a += b` |
| `-=` | `a = a - b` | `a -= b` |
| `*=` | `a = a * b` | `a *= b` |
| `/=` | `a = a / b` | `a /= b` |
| `%=` | `a = a % b` | `a %= b` |

## 3. Toán tử so sánh (Comparison Operators)

| Toán tử | Ý nghĩa | Ví dụ | Kết quả |
|---------|---------|-------|---------|
| `==` | Bằng | `5 == 3` | `false` |
| `!=` | Khác | `5 != 3` | `true` |
| `>` | Lớn hơn | `5 > 3` | `true` |
| `<` | Nhỏ hơn | `5 < 3` | `false` |
| `>=` | Lớn hơn hoặc bằng | `5 >= 5` | `true` |
| `<=` | Nhỏ hơn hoặc bằng | `3 <= 5` | `true` |

## 4. Toán tử logic (Logical Operators)

| Toán tử | Ý nghĩa | Ví dụ | Kết quả |
|---------|---------|-------|---------|
| `&&` | VÀ (AND) | `true && false` | `false` |
| `||` | HOẶC (OR) | `true || false` | `true` |
| `!` | PHỦ ĐỊNH (NOT) | `!true` | `false` |
