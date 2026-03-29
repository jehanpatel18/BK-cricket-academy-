# 🏏 B.K. Cricket Academy — Promotional Website

## Project Overview
A modern, mobile-friendly promotional website for **B.K. Cricket Academy** affiliated with the **Banaskantha District Cricket Association (BDCA)**. The website is based on the academy's official promotional flyer and showcases its services, coach profile, training schedule, and camp registration.

---

## ✅ Completed Features

- **Sticky Navbar** with scroll-activated dark background and mobile hamburger menu
- **Hero Section** with animated background, camp registration badge, and flyer image display
- **Services Section** — 6 service cards (Personal Coaching, Turf & Matting Wicket, Match Practice, Fitness Programme, Boy & Girl Cricket, Video Analysis)
- **Coach Profile** — Ajay Malesalam with credential badges (Gujarat State Player, NIS Certified – Patiala 2024)
- **Training Schedule** — Morning (7–9 AM) and Evening (4–6 PM) cards with venue info
- **Registration Form** — Annual & Summer Camp interest form with API data persistence
- **Contact Section** — Phone, location, hours, and WhatsApp
- **Footer** with quick navigation links
- **Scroll animations** via IntersectionObserver
- **Active nav link highlighting** on scroll
- **Parallax hero background** effect
- **Form validation** with shake feedback and success message
- **Data persistence** via RESTful Table API (registrations table)

---

## 📁 File Structure

```
index.html          ← Main HTML page
css/
  style.css         ← All styles (responsive, themed)
js/
  main.js           ← Interactivity, animations, form handling
README.md           ← Project documentation
```

---

## 🔗 Page Sections (Anchor Links)

| Section     | Anchor URL    | Description                          |
|-------------|---------------|--------------------------------------|
| Home/Hero   | `/#home`      | Main hero with title, CTA, flyer image |
| Services    | `/#services`  | 6 academy service cards              |
| Coach       | `/#coach`     | Coach Ajay Malesalam profile         |
| Schedule    | `/#schedule`  | Morning & Evening training timings   |
| Register    | `/#register`  | Annual & Summer Camp registration form |
| Contact     | `/#contact`   | Phone, location, WhatsApp            |

---

## 🗄️ Data Model

### Table: `registrations`

| Field          | Type     | Description                    |
|----------------|----------|--------------------------------|
| id             | text     | Unique registration ID         |
| player_name    | text     | Full name of the player        |
| age            | number   | Age of the player              |
| gender         | text     | male / female                  |
| session_pref   | text     | morning / evening / both       |
| phone          | text     | Contact number                 |
| submitted_at   | datetime | Timestamp of submission        |

**API Endpoint:** `tables/registrations`  
**Methods:** GET, POST

---

## 🎨 Design Theme

- **Colors:** Yellow (#FFD700), Deep Purple (#2D1B69), Red (#CC0000), Dark Navy (#1a1a2e), White
- **Fonts:** Oswald (headings), Inter (body)
- **Icons:** Font Awesome 6
- **Style:** Bold sports promotional aesthetic matching the original flyer

---

## 📱 Responsive Breakpoints

| Screen        | Layout Changes                    |
|---------------|-----------------------------------|
| > 1024px      | Full 2-column grid layouts        |
| ≤ 1024px      | Single column, stacked sections   |
| ≤ 768px       | Mobile nav, stacked schedules     |
| ≤ 480px       | Compact contact grid, small hero  |

---

## 🚧 Features Not Yet Implemented

- Coach photograph (flyer image shown as reference; actual photo not provided)
- Google Maps embed for academy location
- Social media links (Instagram, Facebook)
- Admin dashboard to view registrations
- WhatsApp auto-message with registration details

---

## 🔜 Recommended Next Steps

1. Replace coach placeholder icon with actual photograph
2. Add Google Maps embed in the Schedule/Contact section
3. Add social media links (Instagram, Facebook, YouTube)
4. Create admin page to view/export registrations
5. Add photo gallery of academy grounds and training sessions
6. SEO optimization (meta tags, structured data)

---

## 📞 Contact Information
- **Phone:** +91 9157859935
- **Venue:** G.D. Modi College Ground, Palanpur, Banaskantha, Gujarat
- **Coach:** Ajay Malesalam (Gujarat State Player, NIS Certified – Patiala 2024)
