---
type: Page
title: requirement cho phần mềm
description: null
icon: 👳
createdAt: '2024-11-26T09:51:52.854Z'
creationDate: 2024-11-26 16:51
modificationDate: 2024-11-26 16:52
tags: [requirement]
coverImage: null
---

Viết **requirements (yêu cầu)** cho phần mềm là một phần quan trọng trong quy trình phát triển phần mềm, giúp đảm bảo các bên liên quan có chung một sự hiểu biết về chức năng và mục tiêu của dự án. Yêu cầu phần mềm thường được chia thành **yêu cầu chức năng** và **yêu cầu phi chức năng**.

---

### **Cách viết requirements phần mềm**

#### 1. **Xác định các bên liên quan**

- Liệt kê các bên liên quan (stakeholders), như khách hàng, người dùng cuối, đội phát triển, quản lý dự án, v.v.

- Tìm hiểu mong muốn, kỳ vọng, và mục tiêu của từng nhóm.

#### 2. **Phân loại yêu cầu**

- **Yêu cầu chức năng (Functional Requirements)**: Miêu tả những gì hệ thống cần làm.

- **Yêu cầu phi chức năng (Non-Functional Requirements)**: Miêu tả cách hệ thống vận hành, như hiệu năng, bảo mật, khả năng mở rộng, giao diện người dùng, v.v.

#### 3. **Viết yêu cầu một cách rõ ràng**

- **Sử dụng ngôn ngữ rõ ràng**: Tránh các thuật ngữ mơ hồ như "tốt", "nhanh", "dễ sử dụng".

- **Cụ thể và đo lường được**: Mỗi yêu cầu nên có thể kiểm tra được thông qua test hoặc đánh giá.

- **Đơn nghĩa**: Mỗi yêu cầu chỉ nên có một ý nghĩa, tránh gây hiểu lầm.

#### 4. **Cấu trúc tài liệu yêu cầu**

Một tài liệu yêu cầu thường bao gồm các phần sau:

---

### **Mẫu cấu trúc tài liệu yêu cầu phần mềm**

#### **1. Giới thiệu**

- **Mục đích**: Mục tiêu của hệ thống hoặc dự án.

- **Phạm vi**: Miêu tả giới hạn của phần mềm, các tính năng chính sẽ phát triển.

- **Định nghĩa**: Giải thích thuật ngữ, từ viết tắt.

#### **2. Yêu cầu chung**

- **Các bên liên quan**: Liệt kê các nhóm sử dụng hoặc bị ảnh hưởng bởi phần mềm.

- **Giả định và phụ thuộc**: Các điều kiện tiên quyết hoặc giả định để hệ thống hoạt động.

#### **3. Yêu cầu chức năng**

- Danh sách chi tiết các chức năng hệ thống sẽ cung cấp.

- **Ví dụ**:

    - Hệ thống cho phép người dùng đăng nhập bằng tài khoản email và mật khẩu.

    - Người dùng có thể tải tệp lên với dung lượng tối đa 20MB.

    - Hệ thống gửi email xác nhận khi người dùng đăng ký tài khoản.

#### **4. Yêu cầu phi chức năng**

- Các tiêu chí kỹ thuật hoặc chất lượng:

    - **Hiệu năng**: Hệ thống xử lý ít nhất 1000 giao dịch/giây.

    - **Bảo mật**: Tất cả mật khẩu phải được mã hóa bằng thuật toán AES-256.

    - **Khả năng mở rộng**: Hệ thống phải hỗ trợ tối đa 10.000 người dùng đồng thời.

    - **Khả dụng**: Hệ thống phải hoạt động 99.9% thời gian trong một năm.

#### **5. Các ràng buộc thiết kế**

- **Nền tảng**: Hệ thống phải chạy trên Windows và Linux.

- **Công cụ phát triển**: Sử dụng Python 3.10 và Django framework.

#### **6. Ưu tiên yêu cầu**

- Gắn mức độ ưu tiên cho từng yêu cầu: **Cao**, **Trung bình**, **Thấp**.

- Giúp đội phát triển tập trung vào các tính năng quan trọng nhất trước.

#### **7. Test và kiểm tra**

- Miêu tả cách các yêu cầu sẽ được kiểm tra.

- **Ví dụ**:

    - Yêu cầu: Người dùng có thể đăng nhập. Test: Nhập tài khoản và mật khẩu đúng, hệ thống cho phép truy cập.

#### **8. Tài liệu tham khảo**

- Bao gồm các tài liệu liên quan, hướng dẫn sử dụng hoặc báo cáo kỹ thuật.

---

### **Tips để viết requirements tốt**

1. **Tập trung vào người dùng**:

    - Miêu tả hành vi của hệ thống từ góc nhìn người dùng (user stories).

    - **Ví dụ**: "Người dùng có thể xem lịch sử giao dịch của họ trong 6 tháng qua."

2. **Tham khảo các chuẩn mực**:

    - Sử dụng các framework hoặc tiêu chuẩn như IEEE 830 để viết yêu cầu.

3. **Sử dụng các công cụ hỗ trợ**:

    - Dùng các công cụ như **JIRA**, **Confluence**, hoặc **Trello** để quản lý và theo dõi yêu cầu.

4. **Đảm bảo tính nhất quán**:

    - Kiểm tra xem các yêu cầu không xung đột với nhau.

---

### **Ví dụ yêu cầu phần mềm**

#### **Yêu cầu chức năng**

1. Hệ thống phải hỗ trợ chức năng đăng nhập bằng email và mật khẩu.

2. Người dùng có thể tìm kiếm sản phẩm theo tên hoặc mã sản phẩm.

3. Hệ thống sẽ gửi thông báo đến email khi đơn hàng được xử lý.

#### **Yêu cầu phi chức năng**

1. Hệ thống phải phản hồi trong vòng 1 giây với 90% yêu cầu của người dùng.

2. Toàn bộ dữ liệu người dùng phải được mã hóa khi lưu trữ.

3. Ứng dụng phải hỗ trợ tiếng Anh và tiếng Việt

