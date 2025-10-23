---
title: "Java Cơ Bản #4: Cấu Trúc Điều Khiển - If/Else và Switch"
subtitle: "Học cách sử dụng câu lệnh điều kiện if-else và switch-case trong Java"
date: 2024-01-26
description: "Học cách sử dụng câu lệnh điều kiện if-else và switch-case trong Java"
tags: ["java", "if-else", "switch", "điều kiện", "cơ bản", "Java Cơ Bản"]
categories: ["Java"]
bigimg:
- src: "/img/hexagon.jpg"
  desc: "Hexagon"
---

## Cấu trúc điều khiển là gì?

**Cấu trúc điều khiển** cho phép chương trình đưa ra quyết định và thực hiện các hành động khác nhau dựa trên điều kiện. Giống như trong cuộc sống, chúng ta thường phải đưa ra quyết định: "Nếu trời mưa thì mang ô, nếu không thì không cần".

## 1. Câu lệnh If

### Cú pháp cơ bản:
```java
if (điều_kiện) {
    // Code thực hiện khi điều kiện đúng
}
```

## 2. Câu lệnh If-Else

### Cú pháp:
```java
if (điều_kiện) {
    // Code khi điều kiện đúng
} else {
    // Code khi điều kiện sai
}
```

## 3. Câu lệnh If-Else If-Else

### Cú pháp:
```java
if (điều_kiện_1) {
    // Code khi điều kiện 1 đúng
} else if (điều_kiện_2) {
    // Code khi điều kiện 2 đúng
} else {
    // Code khi tất cả điều kiện đều sai
}
```

## 4. Câu lệnh Switch-Case

Switch-case được sử dụng khi cần so sánh một biến với nhiều giá trị cụ thể.

### Cú pháp:
```java
switch (biến) {
    case giá_trị_1:
        // Code khi biến == giá_trị_1
        break;
    case giá_trị_2:
        // Code khi biến == giá_trị_2
        break;
    default:
        // Code khi không khớp case nào
        break;
}
```
