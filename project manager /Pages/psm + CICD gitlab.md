---
type: Page
title: psm + CI/CD gitlab
description: null
icon: 😇
createdAt: '2024-11-28T02:22:25.923Z'
creationDate: 2024-11-28 09:22
modificationDate: 2024-11-28 09:22
tags: [psm]
coverImage: null
---

**PSM** (Professional Scrum Master) là một chứng chỉ trong khuôn khổ Scrum, mà chuyên gia Scrum Master phải biết để áp dụng các nguyên lý và phương pháp Scrum vào thực tế trong đội ngũ Agile. Trong ngữ cảnh triển khai ứng dụng ReactJS Portfolio lên GitLab và triển khai tự động (CI/CD), **PSM** có thể áp dụng trong việc hướng dẫn và quản lý quy trình Scrum để đảm bảo dự án triển khai đúng tiến độ và chất lượng.

Dưới đây là cách áp dụng phương pháp **Scrum** (với vai trò của Scrum Master) vào quy trình triển khai dự án ReactJS Portfolio với **CI/CD** và **GitLab**.

### Các bước để áp dụng Scrum trong dự án ReactJS và GitLab CI/CD

#### 1. **Xác định Product Backlog**

Trong Scrum, **Product Backlog** là danh sách các tính năng, yêu cầu và công việc cần hoàn thành. Đối với dự án ReactJS Portfolio, Product Backlog có thể bao gồm các công việc như:

- Thiết kế giao diện người dùng.

- Xây dựng các thành phần (component) trong React.

- Kiểm thử các tính năng.

- Triển khai ứng dụng lên môi trường (sử dụng GitLab CI/CD).

Ví dụ, bạn có thể chia nhỏ các công việc như sau:

- **Tạo layout cho portfolio**.

- **Cài đặt routing** (React Router).

- **Tạo các component** (About, Projects, Contact).

- **Cài đặt và cấu hình Jest để kiểm thử**.

- **Cài đặt GitLab CI/CD pipeline**.

#### 2. **Scrum Team và Sprint Planning**

- **Scrum Team** của bạn có thể bao gồm: Developers (các lập trình viên xây dựng ứng dụng), Product Owner (người xác định yêu cầu và tính năng), và Scrum Master (người quản lý quy trình và giúp nhóm tuân thủ Scrum).

- **Sprint Planning** là một cuộc họp trong đó đội Scrum lập kế hoạch cho một Sprint (thường là 2-4 tuần). Bạn sẽ quyết định các công việc trong **Product Backlog** sẽ được làm trong Sprint này. Ví dụ:

    - Sprint 1 có thể tập trung vào việc xây dựng cấu trúc cơ bản của ứng dụng (giao diện, routing, và một vài component).

    - Sprint 2 có thể tập trung vào việc kiểm thử và cấu hình CI/CD.

#### 3. **Sprint Backlog và thực thi**

- **Sprint Backlog** là danh sách các công việc được chọn từ Product Backlog cho Sprint hiện tại.

- Trong mỗi Sprint, Scrum Master sẽ hỗ trợ đội phát triển để hoàn thành các công việc trong Sprint Backlog.

- Ví dụ, đối với một Sprint, có thể bao gồm các công việc:

    - Cài đặt các thư viện cần thiết cho React.

    - Xây dựng giao diện Portfolio với các component đơn giản.

    - Cấu hình môi trường kiểm thử và GitLab CI/CD.

#### 4. **Daily Scrum (Standup Meeting)**

- Scrum Master tổ chức các cuộc họp **Daily Scrum** (họp 15 phút mỗi ngày) để đội phát triển báo cáo tình hình công việc của mình, chia sẻ khó khăn và cập nhật tiến độ.

- Ví dụ, trong một dự án ReactJS, các lập trình viên có thể báo cáo về việc:

    - Hoàn thành phần xây dựng giao diện.

    - Đang gặp khó khăn với việc cấu hình Jest để kiểm thử.

    - Đã hoàn thành cấu hình CI/CD nhưng chưa deploy thành công.

#### 5. **Sprint Review**

- Cuối mỗi Sprint, Scrum Master tổ chức một cuộc họp **Sprint Review** để trình bày kết quả công việc của Sprint cho Product Owner và các bên liên quan.

- Ví dụ, sau một Sprint, bạn có thể trình bày:

    - Ứng dụng ReactJS đã hoàn thành giao diện cơ bản.

    - Các unit test đã được triển khai và chạy thành công.

    - CI/CD pipeline đã được cấu hình và có thể deploy lên môi trường GitLab Pages hoặc AWS S3.

#### 6. **Sprint Retrospective**

- Sau mỗi Sprint, đội Scrum tổ chức một cuộc họp **Sprint Retrospective** để đánh giá quá trình làm việc và cải tiến quy trình.

- Scrum Master sẽ hỏi đội các câu hỏi như:

    - Những gì đã làm tốt trong Sprint?

    - Những gì cần cải thiện?

    - Các khó khăn gặp phải trong quy trình triển khai CI/CD, như: kiểm thử không chạy đúng, deploy lên GitLab Pages không thành công, v.v.

Dựa trên kết quả của cuộc họp, Scrum Master sẽ giúp đội điều chỉnh và cải thiện quy trình cho Sprint tiếp theo.

#### 7. **Cải tiến quy trình CI/CD liên tục**

- Scrum Master có thể hỗ trợ đội phát triển trong việc cải tiến quy trình **CI/CD**. Ví dụ:

    - Đảm bảo kiểm thử tự động được thực hiện mỗi khi có thay đổi (commit) trong mã nguồn.

    - Tích hợp các công cụ kiểm thử (như Jest, Cypress) vào GitLab CI pipeline.

    - Tự động triển khai ứng dụng lên môi trường GitLab Pages hoặc các dịch vụ khác như AWS hoặc Netlify.

### Các lưu ý khi triển khai Scrum trong CI/CD:

1. **Tạo môi trường kiểm thử và kiểm thử liên tục**:

    - Cấu hình **GitLab CI/CD** để kiểm thử ứng dụng React mỗi khi có thay đổi (push code). Scrum Master sẽ giám sát quá trình này và đảm bảo rằng mọi lỗi được phát hiện sớm trong mỗi Sprint.

2. **Triển khai ứng dụng tự động**:

    - Cấu hình GitLab để tự động deploy ứng dụng lên GitLab Pages, AWS, hoặc Netlify mỗi khi mã nguồn được đẩy lên GitLab (từ nhánh `master` hoặc nhánh chính thức). Điều này giúp đảm bảo rằng ứng dụng luôn được triển khai và cập nhật mới nhất cho người dùng.

3. **Quản lý kỹ thuật và giao tiếp giữa các nhóm**:

    - Scrum Master giúp nhóm quản lý các vấn đề kỹ thuật như **cấu hình môi trường**, **công cụ kiểm thử tự động** và **deploy tự động**, đồng thời đảm bảo mọi thành viên đều hiểu được quy trình và các công cụ đang sử dụng.

### Tóm lại:

Việc triển khai Scrum vào quá trình **CI/CD** sẽ giúp dự án ReactJS của bạn có quy trình làm việc mạch lạc và hiệu quả hơn. **Scrum Master** (PSM) sẽ đảm nhận vai trò hỗ trợ nhóm, giám sát các quy trình như kiểm thử tự động, triển khai tự động, và cải tiến quy trình làm việc liên tục thông qua các Sprint và các cuộc họp Scrum. Bằng cách này, Scrum giúp đảm bảo rằng ứng dụng được phát triển đúng tiến độ, chất lượng và dễ dàng duy trì trong suốt vòng đời phát triển.

