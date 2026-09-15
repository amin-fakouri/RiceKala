# 🍚 RiceKala

<p align="center">
  <strong>A Multi-Vendor Marketplace for Rice</strong>
</p>

<p align="center">
  RiceKala is a specialized marketplace that connects customers with multiple rice sellers,
  allowing them to discover, compare, and choose products from different vendors.
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e9f08af7-c219-496b-b0db-eab635f77490" alt="RiceKala Preview">
</p>

---

## 📌 About

**RiceKala** is a **multi-vendor marketplace platform** built specifically for the rice market.

Unlike a traditional online store where products are managed by a single seller, RiceKala follows a marketplace model where **multiple sellers can list and manage their rice products on the platform**.

Customers can browse available products, compare offerings from different sellers, and choose the product that best fits their needs.

The project was developed as a real-world marketplace application using the **Laravel ecosystem**, with a focus on clean architecture, dynamic interfaces, and scalable application structure.

---

## ✨ Features

* 🛒 **Multi-Vendor Marketplace** — Multiple sellers can offer products through the platform.
* 🏪 **Seller Management** — Sellers can manage their products and marketplace presence.
* 🍚 **Product Management** — Create, manage, and organize rice products.
* 🔎 **Product Discovery** — Customers can browse and explore available products.
* ⚖️ **Seller & Product Comparison** — Compare different offerings before making a decision.
* 👤 **Customer & Seller Workflows** — Separate experiences and functionality for different user types.
* 📊 **Dashboard Management** — Manage marketplace data through dedicated dashboards.
* ⚡ **Dynamic UI** — Interactive interfaces powered by Livewire.
* 📱 **Responsive Design** — Designed to work across different screen sizes.

---

## 🛠️ Tech Stack

| Technology        | Usage                              |
| ----------------- | ---------------------------------- |
| **Laravel 11**    | Backend & application architecture |
| **PHP 8.2+**      | Server-side development            |
| **Livewire 3**    | Dynamic UI & interactions          |
| **Livewire Volt** | Component-based development        |
| **MySQL**         | Database                           |
| **Tailwind CSS**  | UI styling                         |
| **Composer**      | PHP dependency management          |

---

## 📸 Project Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/e9f08af7-c219-496b-b0db-eab635f77490" alt="RiceKala Dashboard">
</p>

---

## 🎯 Project Purpose

RiceKala was built to explore and implement the architecture of a **real-world multi-vendor marketplace**.

The project focuses on:

* Marketplace architecture
* Multi-seller product management
* Customer and seller workflows
* Database relationships
* Authentication and authorization
* Dynamic interfaces with Livewire
* Building scalable Laravel applications

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/amin-fakouri/RiceKala.git
cd RiceKala
```

### 2. Install dependencies

```bash
composer install
```

### 3. Create the environment file

```bash
cp .env.example .env
```

### 4. Generate the application key

```bash
php artisan key:generate
```

### 5. Configure the database

Update your `.env` file with your database credentials:

```env
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

### 6. Run migrations

```bash
php artisan migrate
```

### 7. Start the development server

```bash
php artisan serve
```

The application will be available at:

```text
http://127.0.0.1:8000
```

---

## 📂 Project Structure

The project follows the standard Laravel application structure:

```text
RiceKala/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
└── vendor/
```

---

## 📈 Project Status

🚧 **Active Development**

RiceKala is currently a portfolio and development project focused on building the core functionality of a specialized multi-vendor marketplace.

Additional marketplace features and improvements may be added over time.

---

## 👨‍💻 Author

**Mohammad Amin Fakouri**

Laravel & Livewire Developer
Growing into AI Engineering

* GitHub: [@amin-fakouri](https://github.com/amin-fakouri)

---

## 📄 License

This project is open-sourced under the [MIT License](https://opensource.org/licenses/M)
