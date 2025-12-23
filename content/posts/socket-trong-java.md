---
title: "Socket trong Java là gì?"
date: 2025-12-23
draft: false
---

## Socket là gì?
Socket là điểm giao tiếp giữa hai máy tính thông qua mạng.
Trong Java, socket giúp client và server trao đổi dữ liệu.

## Các lớp chính
- `Socket`: phía client
- `ServerSocket`: phía server

## Ví dụ đơn giản
```java
Socket socket = new Socket("localhost", 1234);
