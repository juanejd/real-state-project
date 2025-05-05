# Real Estate PHP Project

A modern real estate management system built with PHP, MySQL and SASS.

## 🚀 Features

- Property management system
- Admin dashboard
- Real estate agent profiles
- Image upload system
- User authentication
- Responsive design

## 📋 Prerequisites

- PHP 7.4+
- MySQL 5.7+
- Node.js
- Composer

## 🛠️ Installation

1. Clone the repository
```bash
git clone <your-repo-url>
cd bienesRaicesPHP
```

2. Install PHP dependencies
```bash
composer install
```

3. Install Node dependencies
```bash
npm install
```

4. Set up database
```bash
# Import database schema
mysql -u root -p database_name < schema.sql
```

5. Compile assets
```bash
npm run dev
```

## 🗄️ Project Structure

```
├── admin/              # Admin panel
├── includes/          # PHP functions & config
├── src/              # Source files
│   ├── js/          # JavaScript
│   └── scss/        # SASS styles
├── public/           # Public assets
└── vendor/          # Dependencies
```

## 💻 Usage

### Admin Panel
- URL: `/admin`
- Default credentials:
  - Email: admin@example.com
  - Password: 123456

### Property Management
- Add/Edit/Delete properties
- Manage property images
- Set property details

## 🔒 Security

- Password hashing
- SQL injection protection
- XSS prevention
- CSRF protection

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments
* [PHP](https://www.php.net/)
* [MySQL](https://www.mysql.com/)
* [Sass](https://sass-lang.com/)
* [Composer](https://getcomposer.org/)
