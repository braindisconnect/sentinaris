# Sentinaris

### *Faith. Family. Organized.*



**Sentinaris** is an open-source Church Management System (CMS) built for congregations of all sizes. Self-host it for free, or let us handle everything for you.



---



## ✨ Features



- **Member Management** — Track congregation members, families, contact info, and attendance

- **Event & Service Scheduling** — Organize services, events, and ministry calendars

- **Giving & Donations** — Record tithes and offerings, generate giving statements

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

#    Then visit your domain to complete setup

```



---



## 💡 Pricing & Hosting Options



Sentinaris is **free and open source**. You are welcome to use it at no cost as long as you set it up and host it yourself.



| Plan | Price | What's Included |

|---|---|---|

| **Self-Hosted** | Free | Full source code, use as-is |

| **Managed Hosting** | $25–$49/mo | We set up and host your own subdomain (`yourchurch.sentinaris.com`), fully configured |

| **Basic Support** | $20/mo | 2 support tickets/month · 2-business-day response |

| **Premium Support** | $35/mo | 3 support tickets/month · 2-business-day response · 1 video call/month |



> 💛 **Half of all hosting proceeds is donated to our church.**



Managed hosting pricing is based on congregation size:

- Under 100 members → **$25/month**

- 100–500 members → **$39/month**

- 500+ members → **$49/month**



Support tickets do **not** roll over month to month.



To inquire about managed hosting or support, visit: **https://www.sentinaris.com**



---



## 📁 Project Structure



```

sentinaris/

├── index.php            # App entry point

├── config.php           # Database & app configuration

├── sentinaris.sql       # Database schema

├── includes/            # Core PHP includes (layout, auth, helpers)

├── modules/             # Feature modules (members, events, giving, etc.)

├── assets/              # CSS, JS, images

└── README.md

```



---



## 🤝 Contributing



Contributions are welcome! If you find a bug or have a feature request:



[Open an issue](https://github.com/braindisconnect/sentinaris/issues)



Please keep contributions focused on features that benefit small-to-medium churches.




---




## 📄 License



 See [LICENSE](./LICENSE.md) for full terms.



---



## 🙏 About


Sentinaris was built to serve churches — not profit from them. The software is free because every church deserves great tools regardless of budget. When you choose managed hosting, half of the hosting proceeds you pay goes directly back to support our own church's ministry. We built what we wished we had. 

> *"Guarding what matters most."*




---




<p align="center">

  Built with ❤️ for the local church &nbsp;·&nbsp; <a href="https://sentinaris.com">sentinaris.com</a>

</p>
