# Sentinaris
### *Faith. Family. Organized.*

**Sentinaris** is an open-source Church Management System (CMS) built for congregations of all sizes. Self-host it for free, or let us handle everything for you.

---

## ✨ Features

- **Member Management** — Track congregation members, families, contact info, and attendance
- **Event & Service Scheduling** — Organize services, events, and ministry calendars
- **Giving & Donations** — Record tithes and offerings, generate giving statements
- **Volunteer Management** — Schedule and coordinate ministry volunteers
- **Communication Tools** — Send announcements and updates to your congregation
- **Reports & Insights** — Understand your church's growth and engagement
- **Multi-user Roles** — Admin, Pastor, Staff, and Volunteer permission levels
- **Responsive Design** — Works on desktop, tablet, and mobile

---

## 🚀 Getting Started

### Requirements

- PHP 7.4+
- MySQL / MariaDB
- A web server (Apache or Nginx)

### Self-Hosted Installation

```bash
# 1. Clone the repository
git clone https://github.com/braindisconnect/sentinaris.git

# 2. Navigate into the project
cd sentinaris

# 3. Copy and configure your environment
cp config.example.php config.php

# 4. Edit config.php with your database credentials
nano config.php

# 5. Import the database schema
mysql -u your_user -p your_database < sentinaris.sql

# 6. Point your web server document root to the project folder
#    Then visit your domain to complete setup
```

---

## 💡 Pricing & Hosting Options

Sentinaris is **free and open source**. You are welcome to use it at no cost as long as you set it up and host it yourself.

| Plan | Price | What's Included |
|---|---|---|
| **Self-Hosted** | Free | Full source code, use as-is |
| **Managed Hosting** | $25–$49/mo | We set up and host your own subdomain (`yourchurch.sentinaris.com`), fully configured |
| **Basic Support** | $20/mo | 3 support tickets/month · 24hr response |
| **Premium Support** | $35/mo | 5 support tickets/month · 24hr response · 1 video call/month |

> 💛 **Half of all hosting and support revenue is donated to our church.**

Managed hosting pricing is based on congregation size:
- Under 100 members → **$25/month**
- 100–500 members → **$39/month**
- 500+ members → **$49/month**

Support tickets do **not** roll over month to month.

To inquire about managed hosting or support, contact: **support@sentinaris.com**

---

## 📁 Project Structure

```
sentinaris/
├── index.php            # App entry point
├── config.php           # Database & app configuration
├── sentinaris.sql       # Database schema
├── includes/            # Core PHP includes (layout, auth, helpers)
├── modules/             # Feature modules (members, events, giving, etc.)
├── assets/              # CSS, JS, images
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a feature request:

1. [Open an issue](https://github.com/braindisconnect/sentinaris/issues)
2. Fork the repo and create a feature branch
3. Submit a pull request with a clear description of your changes

Please keep contributions focused on features that benefit small-to-medium churches.

---

## 📄 License

Sentinaris is licensed under the **GNU General Public License v3.0 (GPL v3)** — free to use, modify, and distribute. If you distribute Sentinaris or a modified version, you must also make the source code available under the same GPL v3 license. See [LICENSE](./LICENSE) for full terms or visit [gnu.org/licenses/gpl-3.0](https://www.gnu.org/licenses/gpl-3.0).

---

## 🙏 About

Sentinaris was built by a developer who attends and serves a local church, with the goal of giving congregations an affordable, dignified alternative to expensive church software.

> *"Guarding what matters most."*

---

<p align="center">
  Built with ❤️ for the local church &nbsp;·&nbsp; <a href="https://sentinaris.com">sentinaris.com</a>
</p>
