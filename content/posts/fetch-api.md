---
title: "Fetch API trong JavaScript"
date: 2025-12-23
draft: false
---

## Fetch API là gì?
Fetch API dùng để gửi request HTTP từ trình duyệt.

## Ví dụ
```js
fetch("https://api.example.com/data")
  .then(res => res.json())
  .then(data => console.log(data));
