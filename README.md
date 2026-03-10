# 🛒 WebBanHangOnline

> A simple **ASP.NET MVC E-Commerce Web Application** built for learning and practicing web development with **.NET Framework**.

---

# 📌 Giới thiệu

**WebBanHangOnline** là một website bán hàng trực tuyến được xây dựng bằng **ASP.NET MVC (.NET Framework)**.

Hệ thống cho phép người dùng xem danh sách sản phẩm, xem chi tiết sản phẩm và duyệt sản phẩm theo danh mục thông qua giao diện web.

Project được thực hiện nhằm mục đích **học tập và thực hành phát triển web với ASP.NET MVC**, kết hợp với **template giao diện có sẵn** để xây dựng một hệ thống bán hàng cơ bản.

---

# 🚀 Công nghệ sử dụng

| Công nghệ         | Mô tả                                     |
| ----------------- | ----------------------------------------- |
| ASP.NET MVC       | Framework phát triển web theo mô hình MVC |
| C#                | Ngôn ngữ lập trình chính                  |
| Razor View Engine | Engine render giao diện                   |
| SQL Server        | Hệ quản trị cơ sở dữ liệu                 |
| Entity Framework  | ORM hỗ trợ thao tác database              |
| Bootstrap         | Framework giao diện responsive            |
| jQuery            | Thư viện JavaScript                       |

---

# ✨ Chức năng chính

## 👤 Người dùng

* Xem danh sách sản phẩm
* Xem chi tiết sản phẩm
* Duyệt sản phẩm theo danh mục
* Giao diện responsive

## ⚙️ Quản trị (Admin)

* Quản lý sản phẩm
* Quản lý danh mục
* Quản lý dữ liệu hệ thống

---

# 📂 Cấu trúc thư mục

```
WebBanHangOnline
│
├── Controllers      # Xử lý request từ người dùng
├── Models           # Các model dữ liệu
├── Views            # Giao diện Razor (.cshtml)
├── Content          # CSS, JS, hình ảnh, template
├── Scripts          # Javascript
└── App_Data         # Dữ liệu hoặc cấu hình database
```

---

# ⚡ Hướng dẫn cài đặt và chạy project

## 1️⃣ Clone repository

```bash
git clone https://github.com/yourusername/WebBanHangOnline.git
```

---

# 🗄 Cài đặt SQL Server

Nếu máy chưa có SQL Server, hãy tải tại:

SQL Server 2022 Express
https://www.microsoft.com/en-us/sql-server/sql-server-downloads

Sau khi cài đặt SQL Server, nên cài thêm:

SQL Server Management Studio (SSMS)
https://aka.ms/ssmsfullsetup

---

## 2️⃣ Mở project

Mở project bằng **Visual Studio**

```
WebBanHangOnline.sln
```

---

## 3️⃣ Cấu hình Database

Mở file:

```
Web.config
```

Chỉnh sửa **connection string** để kết nối tới SQL Server.

Ví dụ:

```xml
<connectionStrings>
  <add name="DefaultConnection"
       connectionString="Data Source=.;Initial Catalog=WebBanHangOnline;Integrated Security=True"
       providerName="System.Data.SqlClient"/>
</connectionStrings>
```

---

# 🧩 Tạo Database bằng Entity Framework Migration

Mở **Package Manager Console** trong Visual Studio.

## Kiểm tra chi tiết quá trình tạo database

```powershell
update-database -Verbose
```

Lệnh này hiển thị **toàn bộ SQL command được thực thi** khi tạo database.

## Tạo database

```powershell
update-database
```

Sau khi chạy thành công, **database và các bảng sẽ được tạo tự động trong SQL Server**.

---

# 🔐 Tài khoản Admin mặc định

Sau khi chạy project, bạn có thể đăng nhập vào hệ thống quản trị bằng tài khoản mặc định sau:

**Username**

```
admin@gmail.com
```

**Password**

```
Admin@123
```

Tài khoản này có quyền **quản trị hệ thống (Admin)** và có thể:

* Quản lý sản phẩm
* Quản lý danh mục
* Quản lý dữ liệu hệ thống

⚠️ Khuyến nghị: Sau khi đăng nhập lần đầu nên **đổi mật khẩu để đảm bảo bảo mật**.

---

# ▶️ Chạy project

Chạy project bằng:

```
Ctrl + F5
```

hoặc

```
Start Without Debugging
```

---

# 🎨 Giao diện

Project sử dụng **template frontend có sẵn** kết hợp với **Razor View** để xây dựng giao diện website.

Các thư viện frontend chính:

* Bootstrap
* OwlCarousel
* Themify Icons
* Moment.js

---

# 🎯 Mục tiêu project

Project được thực hiện nhằm:

* Thực hành mô hình **MVC trong ASP.NET**
* Làm quen với **Entity Framework (ORM)**
* Hiểu cách **kết nối Database với Web Application**
* Xây dựng **website bán hàng cơ bản**

---

# 👨‍💻 Tác giả

**Group What Ever**

---

# 📄 License

Project được sử dụng cho mục đích **học tập và nghiên cứu**.
