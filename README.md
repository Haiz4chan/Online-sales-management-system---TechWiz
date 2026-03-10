# 🛒 WebBanHangOnline

> A simple **ASP.NET MVC E-Commerce Web Application** built for learning and practicing web development with .NET.

---

## 📌 Giới thiệu

**WebBanHangOnline** là một website bán hàng trực tuyến được xây dựng bằng **ASP.NET MVC (.NET Framework)**.

Hệ thống cho phép người dùng duyệt sản phẩm, xem chi tiết sản phẩm và quản lý dữ liệu bán hàng thông qua giao diện web.

Project được xây dựng với mục đích **học tập và thực hành phát triển web bằng ASP.NET MVC**, kết hợp với **template giao diện có sẵn** để tạo ra một hệ thống bán hàng cơ bản.

---

## 🚀 Công nghệ sử dụng

| Công nghệ         | Mô tả                                     |
| ----------------- | ----------------------------------------- |
| ASP.NET MVC       | Framework phát triển web theo mô hình MVC |
| C#                | Ngôn ngữ lập trình chính                  |
| Razor View Engine | Engine dùng để render giao diện           |
| SQL Server        | Hệ quản trị cơ sở dữ liệu                 |
| Entity Framework  | ORM hỗ trợ thao tác với database          |
| Bootstrap         | Framework giao diện responsive            |
| jQuery            | Thư viện hỗ trợ JavaScript                |

---

## ✨ Chức năng chính

### 👤 Người dùng

* Xem danh sách sản phẩm
* Xem chi tiết sản phẩm
* Duyệt sản phẩm theo danh mục
* Giao diện responsive

### ⚙️ Quản trị (Admin)

* Quản lý sản phẩm
* Quản lý danh mục
* Quản lý dữ liệu hệ thống

---

## 📂 Cấu trúc thư mục

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

## ⚡ Cách chạy project

### 1️⃣ Clone repository

```bash
git clone https://github.com/yourusername/WebBanHangOnline.git
```

### 2️⃣ Mở project

Mở project bằng **Visual Studio**

```
WebBanHangOnline.sln
```

### 3️⃣ Cấu hình Database

Mở file:

```
Web.config
```

Chỉnh sửa **connection string** để kết nối với SQL Server.

Ví dụ:

```xml
<connectionStrings>
  <add name="DefaultConnection"
       connectionString="Data Source=.;Initial Catalog=WebBanHangOnline;Integrated Security=True"
       providerName="System.Data.SqlClient"/>
</connectionStrings>
```

### 4️⃣ Chạy project

Chạy project bằng:

```
Ctrl + F5
```

hoặc

```
Start Without Debugging
```

---

## 🎨 Giao diện

Project sử dụng **template frontend có sẵn** kết hợp với **Razor View** để xây dựng giao diện hiển thị sản phẩm.

Các thư viện frontend chính:

* Bootstrap
* OwlCarousel
* Themify Icons
* Moment.js

---

## 🎯 Mục tiêu project

Project được thực hiện nhằm:

* Thực hành mô hình **MVC trong ASP.NET**
* Làm quen với **Entity Framework (ORM)**
* Hiểu cách **kết nối Database với Web Application**
* Xây dựng **website bán hàng cơ bản**

---

## 👨‍💻 Tác giả

**Group What Ever**

---

## 📄 License

Project được sử dụng cho mục đích **học tập và nghiên cứu**.
