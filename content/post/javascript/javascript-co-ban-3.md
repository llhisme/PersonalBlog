---
title: "JavaScript Cơ Bản #3: Hàm (Functions) và Scope"
subtitle: "Tìm hiểu về hàm trong JavaScript, các cách định nghĩa hàm và khái niệm scope"
date: 2024-02-03
description: "Tìm hiểu về hàm trong JavaScript, các cách định nghĩa hàm và khái niệm scope"
tags: ["javascript", "hàm", "function", "scope", "cơ bản", "JavaScript Cơ Bản"]
categories: ["JavaScript"]
bigimg:
- src: "/PersonalBlog/img/hexagon.jpg"
---

## Hàm là gì?

**Hàm** (Function) là một khối code có thể tái sử dụng, thực hiện một nhiệm vụ cụ thể. Hàm giúp code trở nên có tổ chức, dễ đọc và dễ bảo trì.

## Các cách định nghĩa hàm

### 1. Function Declaration (Khai báo hàm)

```javascript
function tinhTong(a, b) {
    return a + b;
}
```

### 2. Function Expression (Biểu thức hàm)

```javascript
const tinhHieu = function(a, b) {
    return a - b;
};
```

### 3. Arrow Function (Hàm mũi tên - ES6)

```javascript
const tinhTich = (a, b) => a * b;
```

## Scope (Phạm vi)

Scope xác định khả năng truy cập của các biến.

- **Global Scope**: Biến được khai báo bên ngoài bất kỳ hàm nào.
- **Function Scope**: Biến được khai báo bên trong một hàm.
- **Block Scope**: Biến được khai báo bên trong một khối lệnh (với `let` và `const`).
