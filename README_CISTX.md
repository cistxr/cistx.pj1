# 🌐 CISTX – Integrated Knowledge Web System

> A unified, modular knowledge platform combining public, deep, and hidden data layers.  
> Designed to integrate seamlessly with point-based access, role control, and future app support.

---

## 📘 About CISTX

**CISTX** (Center for Integrated Science and Technology Exchange) is a knowledge-sharing platform that organizes information into three core layers:

- 🌞 **Bright Data**: Public and open-access knowledge  
- 🔷 **Deep Data**: Advanced materials accessible via learning Points  
- 🌑 **Dark Data**: Sensitive or developmental data, restricted access  

The website is designed as the central infrastructure for users to:
- Browse curated resources  
- Unlock deeper content via earned points  
- Contribute, learn, and grow within a gamified system  
- Prepare for eventual app integration (PWA-ready)

---

## 🧩 Core Features

| Feature            | Description |
|-------------------|-------------|
| 🔐 Role-based Access | Guest, Member, Deep User, Admin, Teams |
| 🎯 Point System     | Earn by learning, spend to unlock Deep Data |
| 📂 Zone Selection   | Explore Bright / Deep / Dark layers |
| 📘 Learning Module  | Guided materials & interactive paths |
| 🛒 Shop             | Redeem points for features & content |
| 🛠️ Admin Panel      | Manage users, roles, uploads, and moderation |

---

## ⚙️ Tech Stack

- **Backend**: FastAPI (Python)
- **Frontend**: HTML + Tailwind CSS (Jinja2)
- **Database**: SQLite (dev) / PostgreSQL (prod-ready)
- **Authentication**: Role-based (custom session/cookie system)
- **Hosting**: Replit / Render / Custom VPS (optional)

---

## 📁 Project Structure

```
📦 cistx_project/
├── main.py                  # FastAPI app entry point
├── templates/               # Jinja2 HTML templates
│   ├── base.html
│   ├── home.html
│   ├── zone.html
│   ├── bright.html
│   ├── ...
├── static/                  # CSS, JS, images
├── routers/                 # Route logic for each module
│   ├── bright.py
│   ├── deep.py
│   ├── shop.py
│   └── ...
├── models/                  # SQLModel database schema
├── auth/                    # Login/register/session logic
├── utils/                   # Helper functions
└── README.md
```

---

## 🚧 Current Progress

- ✅ Home, Zone, Bright pages designed  
- ✅ Deep access logic planned (Point-based)  
- ✅ Role system outlined  
- 🚧 Shop, Learning, Admin under construction  
- 🚀 Mobile-friendly & PWA-ready

---

## 📌 Vision

> CISTX aims to reshape digital learning by blending gamification, open access, and deep exploration.  
> It’s not just a website — it's an evolving ecosystem of integrated knowledge.

---

## 🤝 Contributing

Want to help?  
We welcome content curators, developers, and testers.  
Please contact: **cistx.center [at] gmail.com** or open an issue!

---

## 📄 License

MIT License — use freely, attribute responsibly.
