# Phân tích và Xây dựng Cấu Trúc Website Template

## 1. Phân tích cấu trúc trang web mẫu (Tham chiếu: Tech News & Portfolio Portal)
Trang web được thiết kế và tổ chức theo 4 khu vực chức năng cơ bản, phổ biến trên các hệ thống website hiện đại:

- **Header:** Đặt ở vị trí trên cùng của trang web, chứa tiêu đề thương hiệu chính và slogan ngắn gọn giúp người dùng nhận diện ngay định vị của website khi vừa truy cập.
- **Navigation Menu:** Thanh điều hướng đặt ngay phía dưới hoặc tích hợp chung với Header gồm 5 mục chính (*Trang chủ, Tin tức, Dịch vụ, Dự án, Liên hệ*). Menu sử dụng Flexbox để dàn hàng ngang, có hiệu ứng hover đổi màu khi rê chuột.
- **Content Section:** Là khu vực nội dung trọng tâm của trang, chia làm hai phần:
  - *Main Content (bên trái):* Bao gồm tiêu đề bài viết, đoạn văn bản mô tả chi tiết và hình ảnh minh họa thực tế được tối ưu hóa hiển thị.
  - *Sidebar (bên phải):* Đặt các liên kết tiện ích bổ trợ, danh mục nhanh và thông tin phụ.
- **Footer:** Đặt cố định ở chân trang, chứa thông tin bản quyền tác quyền (Copyright © 2026 Đinh Xuân Mạnh) và các liên kết chính sách cơ bản.

---

## 2. Tổ chức thư mục dự án
```text
website-template-structure-analysis/
├── index.html       # File cấu trúc HTML chuẩn Semantic
├── style.css        # File định dạng CSS cho toàn bộ layout
└── README.md        # Văn bản phân tích cấu trúc chi tiết
