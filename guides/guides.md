# <p align="center"> BOOKINGCARE WEBSITE PROJECT TUTORIAL </p> 
***
## Overview
| Module | Title | Learning Outcomes | Time |
|:-------|:------|:-----|:-----|
| 1 | Preparing to Become a Fullstack Developer | Setup development environment successfully <br> Understand basic Git workflow | 4h |
| 2 | Backend with NodeJS & Relational Database | Build basic backend API with Express and Database <br> Perform CRUD with Sequelize ORM | 7h |
| 3 | Authentication & Authorization | Secure backend with JWT <br> Implement role-based authorization | 6h |
| 4 | React Basics | Understand React fundamentals <br> Connect frontend to backend APIs | 12h |
| 5 | Database Analysis & Design | Design ERD for BookingCare system <br> Implement Sequelize relationships | 6h |
| 6 | BookingCare UI Clone | Rebuild BookingCare homepage UI <br> Implement multi-language support | 9h |
| 7 | State Management with Redux | Manage app state with Redux Toolkit <br> Implement role-based UI | 10h |
| 8 | Completing Doctor Information Section | Store doctor information in DB <br> Display doctors dynamically on UI | 10h |
| 9 | Appointment Booking Feature | Build booking feature with modal <br> Send confirmation emails with NodeMailer | 18h |
| 10 | Doctor Management Features | Manage clinic & specialty data <br> Handle doctor-patient interaction | 11h |
| 11 | Application Deployment & Database Migration | Deploy fullstack app to cloud <br> Integrate social plugins | 5h |
| 12 | Docker & DevOps | Containerize backend & frontend <br> Use Docker Compose for multi-service apps | 6h |
---
## Table Of Contents
### [1. Preparing to Become a Fullstack Developer](getting-started/environment-setup.md)
### [2. Backend with NodeJS & Relational Database](backend)<br>
####    [a. NodeJS](backend/nodejs-api.md)
####    [b. Database](backend/database-design.md)
### [3. Authentication & Authorization](backend/authentication.md)
### [4. React Basics](frontend/react-setup.md)
### [5. Database Analysis & Design](backend/database-design.md)
### [6. BookingCare UI Clone](frontend/ui-components.md)
### [7. State Management with Redux](frontend/redux.md)
### [8. Completing Doctor Information Section](reference/case-studies/doctor-info.md)
### [9. Appointment Booking Feature](reference/case-studies/appointment-booking.md)
### [10. Doctor Management Features](reference/case-studies/doctor-management.md)
### [11. Application Deployment & Database Migration](getting-started/deployment-docker.md)
### [12. Docker & DevOps](reference/docker-cheatsheet.md)
---
## Main Content
### 1. Preparing to Become a Fullstack Developer (4h)
- Foundational knowledge to prepare<br>
 :point_right: Kiến thức nền tảng cần chuẩn bị
- Environment setup: VSCode, NodeJS, Git<br>
 :point_right: Cài đặt môi trường: VSCode, NodeJS, Git
- Basic HTML, CSS, SCSS<br>
 :point_right: HTML, CSS, SCSS cơ bản
- Basic Git/GitHub<br>
 :point_right: Git/GitHub cơ bản
***
### 2. Backend with NodeJS & Relational Database (7h)
- What is Node.js?<br>
 :point_right: NodeJS là gì?
- Creating a backend server with Express and Database<br>
 :point_right: Tạo server backend với Express và CSDL
- Basic CRUD with MySQL/PostgreSQL + Sequelize ORM<br>
 :point_right: CRUD với MySQL/PostgreSQL qua Sequelize ORM
- Testing APIs with Postman<br>
 :point_right: Kiểm thử API bằng Postman
***
### 3. Authentication & Authorization (6h)
- Introduction: Authentication & Authorization<br>
 :point_right: Giới thiệu: Authentication & Authorization
- JWT (Access token + Refresh token)<br>
 :point_right: JWT (Access token + Refresh token)
- User authentication middleware<br>
 :point_right: Middleware xác thực người dùng
- API role-based authorization (roles: user, doctor, admin)<br>
 :point_right: Phân quyền API theo role (user, doctor, admin)
- Practice: protect CRUD APIs<br>
 :point_right: Thực hành: bảo vệ API CRUD
***
### 4. React Basics (12h)
- Why choose React (vs Angular/Vue)<br>
 :point_right: Tại sao chọn React (so với Angular/Vue)?
- React core: state, props, event, lifecycle<br>
 :point_right: React cơ bản: state, props, event, lifecycle
- Connecting APIs to Server backend NodeJS<br>
 :point_right: Kết nối API tới Server Backend NodeJS
- CRUD with React + Axios<br>
 :point_right: CRUD với React và Axios
***
### 5. Database Analysis & Design (6h)
- Requirement analysis → ERD (Entity Relationship Diagram)<br>
 :point_right: Phân tích requirement → ERD (Entity Relationship Diagram)
- Types of relationships (1-n, n-n)<br>
 :point_right: Các loại quan hệ (1-n, n-n)
- Data normalization, avoiding redundancy<br>
 :point_right: Chuẩn hoá dữ liệu, tránh dư thừa
- Advanced Sequelize relationships<br>
 :point_right: Quan hệ nâng cao trong Sequelize
- Practice: design User, Doctor, Appointment, Clinic, Specialty tables<br>
 :point_right: Thực hành: thiết kế bảng User, Doctor, Appointment, Clinic, Specialty
***
### 6. BookingCare UI Clone (9h)
- Build BookingCare Home Page (based on [bookingcare.vn](https://bookingcare.vn/))<br>
 :point_right: Xây dựng trang chủ BookingCare (tham chiếu bookingcare.vn)
- Integrate React-slider-carousel library<br>
 :point_right: Tích hợp thư viện: React-slider-carousel
- Multi-language interface (English - Vietnamese)<br>
 :point_right: Giao diện đa ngôn ngữ (Anh - Việt)
***
### 7. State Management with Redux (10h)
- Introduction to Redux Toolkit<br>
 :point_right: Giới thiệu Redux Toolkit
- Multi-language with Redux<br>
 :point_right: Đa ngôn ngữ với Redux
- Role-based menu (admin, user)<br>
 :point_right: Menu phân quyền theo Role người dùng (admin, user)
- CRUD with Redux<br>
 :point_right: CRUD với Redux
***
### 8. Completing Doctor Information Section (10h)
- Handle images/files with MySQL (BLOB in DB)<br>
 :point_right: Xử lý ảnh/tệp với MySQL (BLOB trong DB)
- Create blog with Markdown<br>
 :point_right: Tạo blog bằng Markdown
- Sequelize Relationship (Eager loading)<br>
 :point_right: Quan hệ Sequelize (Eager loading)
- "Featured Doctors" & "Doctor Details"<br>
 :point_right: Hoàn thiện mục 'Bác sĩ nổi bật' & 'chi tiết bác sĩ'
***
### 9. Appointment Booking Feature (18h)
- CRUD schedule by time (left section)<br>
 :point_right: Quản lý lịch khám theo khung giờ (section-left)
- CRUD appointment booking (right section)<br>
 :point_right: Quản lý thông tin đặt lịch khám bệnh (section-right)
- Booking modal<br>
 :point_right: Modal đặt lịch khám bệnh
- Send booking confirmation emails via NodeMailer<br>
 :point_right: Gửi email xác nhận lịch hẹn qua Nodemailer
***
### 10. Doctor Management Features (11h)
- CRUD Clinic<br>
 :point_right: Quản lý danh sách phòng khám (cơ sở y tế)
- CRUD Specialty<br>
 :point_right: Quản lý danh sách chuyên khoa
- Display doctors by clinic/specialty<br>
 :point_right: Hiển thị danh sách bác sĩ theo phòng khám/chuyên khoa
- Thinking in React (reusable components)<br>
 :point_right: Tư duy trong React (tái sử dụng components)
- Patient booking list<br>
 :point_right: Hiển thị danh sách bệnh nhân đặt lịch với bác sĩ
- Send invoices/prescriptions (NodeMailer + attachment)<br>
 :point_right: Gửi hoá đơn/đơn thuốc cho bệnh nhân (đính kèm qua email với NodeMailer)
***
### 11. Application Deployment & Database Migration (5h)
- Migrate DB to PostgreSQL<br>
 :point_right: Chuyển DB sang PostgreSQL
- Deploy Node.js backend (Render, Railway, VPS)<br>
 :point_right: Deploy ứng dụng NodeJS (Render, Railway, VPS)
- Deploy React frontend (Vercel/Netlify)<br>
 :point_right: Deploy ứng dụng React (Vercel/Netlify)
- Integrate Social Plugins (Facebook Like/Share/Comment)<br>
 :point_right: Tích hợp Social Plugin (Facebook Like/Share/Comment)
- Embed Facebook Chat Plugin<br>
 :point_right: Nhúng Facebook Chat Plugin
***
### 12. Docker & DevOps (6h)
- What is Docker and why use it<br>
 :point_right: Docker là gì và tại sao dùng Docker?
- Writing Dockerfile for Node.js backend<br>
 :point_right: Viết Dockerfile cho ứng dụng NodeJS
- Dockerize the React frontend<br>
 :point_right: Dockerize ứng dụng React
- Docker Compose (Node + Postgres + Redis)<br>
 :point_right: Docker Compose (Node + Postgres + Redis)
- Deploy Docker app to VPS/Cloud<br>
 :point_right: Deploy ứng dụng Docker lên VPS/Cloud
***
## Video Tutorial

[Video Playlist](https://www.youtube.com/playlist?list=PLncHg6Kn2JT6E38Z3kit9Hnif1xC_9VqI)

---
