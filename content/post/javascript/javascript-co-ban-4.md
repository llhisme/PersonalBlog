---
title: "JavaScript Cơ Bản #4: DOM và Events"
subtitle: "Tìm hiểu về Document Object Model (DOM) và cách xử lý sự kiện trong JavaScript"
date: 2024-02-05
description: "Tìm hiểu về Document Object Model (DOM) và cách xử lý sự kiện trong JavaScript"
tags: ["javascript", "dom", "events", "cơ bản", "JavaScript Cơ Bản"]
categories: ["JavaScript"]
bigimg:
- src: "/PersonalBlog/img/hexagon.jpg"
  desc: "Hexagon"
---

## DOM là gì?

**DOM** (Document Object Model) là một giao diện lập trình cho các tài liệu HTML và XML. Nó biểu diễn cấu trúc của tài liệu dưới dạng một cây các đối tượng, cho phép JavaScript truy cập và thay đổi nội dung, cấu trúc và kiểu dáng của trang web.

## Truy cập các phần tử DOM

- `getElementById()`: Lấy một phần tử theo ID.
- `getElementsByTagName()`: Lấy một danh sách các phần tử theo tên thẻ.
- `getElementsByClassName()`: Lấy một danh sách các phần tử theo tên lớp.
- `querySelector()`: Lấy phần tử đầu tiên khớp với một bộ chọn CSS.
- `querySelectorAll()`: Lấy một danh sách các phần tử khớp với một bộ chọn CSS.

## Thay đổi nội dung DOM

- `innerHTML`: Thay đổi nội dung HTML của một phần tử.
- `textContent`: Thay đổi nội dung văn bản của một phần tử.
- `setAttribute()`: Thay đổi giá trị của một thuộc tính.
- `style`: Thay đổi kiểu dáng của một phần tử.

## Events (Sự kiện)

Events là các hành động xảy ra trên trang web, chẳng hạn như nhấp chuột, nhấn phím, hoặc tải trang.

### Xử lý sự kiện

- **Thuộc tính HTML `on...`**: `onclick`, `onmouseover`, v.v.
- **Thuộc tính DOM `on...`**: `element.onclick = function() { ... };`
- `addEventListener()`: Phương thức hiện đại và linh hoạt nhất để xử lý sự kiện.

```javascript
const button = document.getElementById("myButton");

button.addEventListener("click", function() {
    alert("Button was clicked!");
});
```
