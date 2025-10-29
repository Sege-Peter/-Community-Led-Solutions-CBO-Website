

```
# 🌍 Community-Led Solutions CBO Website

A modern and responsive **Community-Based Organization (CBO)** website built by **Skope Designs**, designed to empower communities through transparency, sustainability, and youth engagement.  
This website highlights the organization’s projects, mission, and impact in promoting community development and advocacy.

---

## 🧩 Project Overview

**Community-Led Solutions CBO Website** serves as an online presence for the organization, offering:
- Information about the CBO’s mission, vision, and values.
- Updates on ongoing community projects and initiatives.
- Opportunities for youth involvement, volunteering, and partnerships.
- Contact and feedback channels for collaboration and outreach.

---

## 🛠️ Tech Stack

| Component | Technology Used |
|------------|----------------|
| **Frontend** | HTML5, Tailwind CSS, JavaScript |
| **Backend** | PHP (XAMPP) |
| **Database** | MySQL |
| **Server** | Apache (via XAMPP) |
| **Design** | Tailwind UI, Figma (by Skope Designs) |

---

## ⚙️ Key Features

### 🏠 Public Pages
- **Home Page:** Highlights mission, vision, and community programs.
- **About Us:** Story, team, and objectives of the CBO.
- **Projects Page:** Displays ongoing and completed community projects.
- **Get Involved:** Volunteer, donate, or partner with the CBO.
- **Contact Page:** Direct contact form for feedback and inquiries.

### 🔐 Admin Panel
- Secure admin login for authorized users.
- Manage projects, team members, and blog posts.
- View messages received through the contact form.
- Update organizational details dynamically.

---

## 🧾 Folder Structure

```

CommunityLedSolutions/
│
├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
│
├── includes/
│   ├── header.php
│   ├── footer.php
│
├── pages/
│   ├── about.php
│   ├── projects.php
│   ├── contact.php
│   ├── get-involved.php
│
├── admin/
│   ├── index.php
│   ├── dashboard.php
│   ├── manage-projects.php
│
├── database/
│   └── connection.php
│
├── index.php
└── README.md

````

---

## 🗄️ Database Setup

### **Database Name:** `community_led_solutions`

#### Tables
1. `admins` – Stores admin credentials.
2. `projects` – Contains project details.
3. `messages` – Stores contact form submissions.
4. `volunteers` – Details of volunteers and partners.

**Import the SQL file** provided in the `/database` folder into your MySQL using phpMyAdmin.

---

## 💡 Installation Guide

1. **Install XAMPP**
   - Download and install [XAMPP](https://www.apachefriends.org/download.html)
   - Start **Apache** and **MySQL**

2. **Project Setup**
   - Copy the project folder `CommunityLedSolutions` to:
     ```
     C:\xampp\htdocs\
     ```

3. **Database Configuration**
   - Open [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   - Create a database named `community_led_solutions`
   - Import `community_led_solutions.sql` file

4. **Run the Website**
   - Visit [http://localhost/CommunityLedSolutions](http://localhost/CommunityLedSolutions)

5. **Admin Login**
   - URL: `/admin`
   - Default credentials:
     - **Username:** admin  
     - **Password:** password

---

## 🎨 Designed & Developed by

**👨‍💻 Skope Designs**  
Creative Studio for Digital Excellence  

- 🌐 Website: [Skope Designs](https://SkopeDesigns.CO.KE/)  
- 📧 Email: segepeter71@gmail.com  
- 📱 Phone: +254 742 380 183  
- 🧠 Founder: [Sege Peter](https://linkedin.com/in/peter-sege-221831303)  
- 📸 Facebook: [Skope Designs](https://www.facebook.com/Skope)  
- 🎥 YouTube: [@engskope](https://www.youtube.com/@engskope)  
- 🐦 Twitter: [@sege_peter79144](https://x.com/sege_peter79144)

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this code for educational or community development purposes.

---

## ❤️ Acknowledgments

Special thanks to the **Community-Led Solutions CBO** team and all volunteers supporting grassroots development.

> *“Together, we build sustainable communities through collaboration and innovation.”* — Skope Designs
```
