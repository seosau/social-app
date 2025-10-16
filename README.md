# 🌐 Social App — Microservice-based Social Network

Một ứng dụng **mạng xã hội** hiện đại được xây dựng theo **kiến trúc microservice**, cho phép người dùng kết nối, đăng bài, trò chuyện, tương tác và nhận thông báo theo thời gian thực.

---

## 🧱 Kiến trúc tổng quan

Dự án được thiết kế theo mô hình **Microservice Architecture**, chia thành nhiều dịch vụ độc lập để dễ mở rộng và triển khai


## ⚙️ Công nghệ sử dụng

| Thành phần | Công nghệ |
|-------------|------------|
| **Frontend** | React, Next.js, Tailwind CSS |
| **Backend services** | Node.js (Express / NestJS), TypeScript |
| **Database** | MongoDB / PostgreSQL |
| **Message queue** | RabbitMQ / Kafka |
| **API Gateway** | Nginx / Express Gateway |
| **Authentication** | JWT, OAuth2 |
| **Realtime** | Socket.IO / WebSocket |
| **Containerization** | Docker, Docker Compose |
| **Deployment** | AWS / DigitalOcean / Render |

---

## 🚀 Chức năng chính

- 🔐 **Đăng ký / đăng nhập / xác thực**
- 📝 **Đăng bài viết, bình luận, tương tác (like/share)**
- 💬 **Chat realtime giữa người dùng**
- 📸 **Story tự xoá sau 24h**
- 🔔 **Thông báo (notification) realtime**
- ⚙️ **Hàng đợi xử lý nền (worker-service)**

---

## 📁 Liên kết các service

| Service | Repo link |
|----------|------------|
| 🌐 Frontend | [frontend](https://github.com/username/social-app-frontend) |
| 🧩 API Gateway | [api-gateway](https://github.com/username/social-app-api-gateway) |
| 🧑‍💼 User Service | [user-service](https://github.com/username/social-app-user-service) |
| 💬 Chat Service | [chat-service](https://github.com/username/social-app-chat-service) |
| 📝 Comment Service | [comment-service](https://github.com/username/social-app-comment-service) |
| ❤️ Engagement Service | [engagement](https://github.com/username/social-app-like-service) |
| 📢 Notification Service | [notif-service](https://github.com/username/social-app-notif-service) |
| 📚 Story Service | [story-service](https://github.com/username/social-app-story-service) |
| ⚙️ Worker Service | [worker-service](https://github.com/username/social-app-worker-service) |
| 🚪 WS Gateway | [ws-gateway](https://github.com/username/social-app-ws-gateway) |

---

## 🧭 Mục tiêu thiết kế

- Kiến trúc **tách biệt rõ ràng**, dễ mở rộng và bảo trì.  
- Hỗ trợ **triển khai độc lập** từng service.  
- Có thể thay thế, nâng cấp công nghệ mà không ảnh hưởng toàn hệ thống.  
- Chuẩn bị sẵn cho **CI/CD và scaling trên cloud**.

---

## 🧑‍💻 Tác giả

**[Ma Seo Sầu]**  
📧 Email: seosausau@gmail.com  
🔗 GitHub: [github.com/seosau](https://github.com/seosau)  
💼 LinkedIn: [linkedin.com/in/maseosau](https://www.linkedin.com/in/maseosau)

---

## 🏗️ Ghi chú

Dự án được xây dựng với mục tiêu **học tập, demo kiến trúc microservice** và có thể mở rộng thêm:
- AI recommendation (gợi ý bạn bè / nội dung)
- Video upload / stream
- Monitoring (Prometheus / Grafana)

