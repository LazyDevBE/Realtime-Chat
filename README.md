# 💬 Moji - Real-time Chat Application

> Ứng dụng trò chuyện thời gian thực xây dựng với React, Node.js (Express), MongoDB và Socket.io.

![Moji Chat Banner](https://via.placeholder.com/800x400?text=Moji+Chat+App+Preview) <!-- Thay bằng link ảnh/GIF demo giao diện của bạn nếu có -->

---

## 📌 Tổng quan dự án

**Moji** là hệ thống nhắn tin thời gian thực đa nền tảng, hỗ trợ trò chuyện 1-1, chat nhóm, đính kèm hình ảnh và quản lý trạng thái bạn bè theo thời gian thực. Dự án được thiết kế với tiêu chuẩn bảo mật cao (JWT Authentication qua HttpOnly Cookie, mã hóa mật khẩu Bcrypt) và tối ưu hóa trải nghiệm người dùng (Infinite Scroll, Auto-reconnect Socket, Responsive UI).

---

## 📚 Tài liệu kiến trúc & Đặc tả hệ thống (SRS)

Toàn bộ tài liệu phân tích nghiệp vụ, kiến trúc kỹ thuật và đặc tả chi tiết đã được đóng gói tại thư mục `docs/`:

## 👉 **[Xem chi tiết Tài liệu Đặc tả Yêu cầu Phần mềm (SRS.md)](./docs/SRS.md)**

---

## 🛠️ Công nghệ sử dụng (Tech Stack)

| Phân hệ             | Công nghệ / Thư viện chính                                                                  |
| :------------------ | :------------------------------------------------------------------------------------------ |
| **Frontend**        | ReactJS, Vite, Tailwind CSS, Shadcn UI, Zustand (State Management), Socket.io Client, Axios |
| **Backend**         | Node.js, Express.js, Socket.io Server, JWT (JsonWebToken), Bcrypt, Multer                   |
| **Database**        | MongoDB Atlas (Mongoose ODM)                                                                |
| **Storage & Tools** | Cloudinary API (Media Management), Swagger UI (API Docs)                                    |

---
