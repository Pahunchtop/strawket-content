---
title: "Strawket Website Overview"
author: "Admin"
tags: ""
date: "2025-07-04"
image: "search.png"
---


## 🏫 Strawket Website Overview

Strawket is a privacy-focused educational platform built for students, instructors, and admins to collaboratively engage in learning, wellness, and content sharing. It is designed to work without a traditional backend by leveraging GitHub and Google Sheets for content and data management.

---

### ✨ Key Modules & Features

#### 🎓 Student Dashboard
- Browse and read educational and motivational **blogs**
- **Book sessions** with yoga/wellness instructors
- Perform **wellness assessments**
- View **automated reports** based on quiz responses
- Access personalized user dashboard

#### 🧘 Instructor Panel
- Add **live sessions**, **blogs**, and **testimonials**
- Manage personal profile and content contributions
- Feature in search results via AI-matching

#### 🛡️ Admin Panel
- View and manage **all users** and **instructors**
- Approve or delete **blogs** and **testimonials**
- Review **Contact Us** submissions (stored in Google Sheets)
- Trigger GitHub workflows for content publishing

---

### 🗃️ Tech Stack & Architecture

| Layer | Technology |
|-------|------------|
| Frontend | React |
| Content Storage | GitHub Markdown (`posts/`, `tests/`, `images/`) |
| Forms | Google Apps Script Web Apps (Contact & Subscribe forms) |
| Authentication | JWT + CSRF tokens |
| Deployment | No backend, lightweight client-only app |

---

### 🔒 Privacy & Security

- **No personal data stored** in a traditional database
- Blog/testimonial creation secured via GitHub Actions and private content repo
- Content displayed from **public `strawket-content`** repo (read-only)
- **Branch protection rules** prevent unauthorized commits or edits
- Forms protected with **CORS-safe Google Scripts**

---

### 📚 Blog Topics

- Mindfulness & Meditation
- Spiritual Experiences (e.g. Khatu Shyam Ji Temple)
- Instructor Spotlights
- Productivity Hacks for Learners
- Yoga & Wellness Tips

---

### 🔗 External Integrations

- [📷 Instagram](https://www.instagram.com/strawketlearning)
- [🎥 YouTube](https://youtube.com/@strawket)
- [📘 Facebook](https://www.facebook.com/share/16iw7U1H5J)
- [📅 Book a Demo (TidyCal)](https://tidycal.com/deepak-strawket/strawket-product-demo)

---

### 🚀 Future Suggestions

- Add pagination to blog and testimonial listing
- Include rich SEO metadata per blog detail page
- Allow admin to reorder featured content manually
- Support image upload preview before publishing testimonials

---

🛠️ **Maintained by**: `Pahunchtop`  
🔗 **Live Site**: [strawket.com](https://strawket.com)

