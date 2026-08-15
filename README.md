# SS Grand Inn — Digital Guest Portal 🏨

A mobile-first, QR-code-based digital guest experience website built for **SS Grand Inn**, a hotel located opposite Samarlakota Railway Station, Kakinada District, Andhra Pradesh. Guests scan a QR code placed in their room to access hotel services, order food, get local recommendations, and reach support — without needing to install an app.

Built entirely with **HTML** (styling and interactivity embedded directly in each page via `<style>` and `<script>` tags — no external CSS/JS files), with a bilingual **English / Telugu** interface throughout.

## ✨ Features

| Page | Purpose |
|------|---------|
| `index.html` | Welcome / landing screen with hotel name and "Get Started" entry point |
| `home.html` | Main guest dashboard — quick links to all services, WhatsApp support shortcut |
| `food.html` | In-room dining menu (Breakfast, Lunch, Dinner, Snacks, Beverages) with category filters and pricing in ₹ |
| `wifi.html` | Guest WiFi network name & password with one-tap copy-to-clipboard |
| `support.html` | Guest support center — housekeeping, food, WiFi issues, extra bedding, taxi, laundry — sent directly via WhatsApp with room number |
| `explore.html` | Nearby attractions (temples, beach, wildlife sanctuary, railway station, city center) with distances from the hotel |
| `info.html` | Hotel information — check-in/out times, restaurant hours, facilities, and location |

**Other highlights:**
- 🌐 English/Telugu language toggle on every page (persisted via `localStorage`)
- 💬 Direct WhatsApp integration for support requests and staff assistance, auto-tagged with the guest's room number
- 📱 Fully responsive, mobile-first layout designed for QR-code scanning on guest phones
- 🎨 Consistent luxury navy-and-gold hotel branding across all pages

## 🛠️ Tech Stack

- **HTML5** — page structure and content
- **CSS3** — styling and responsive layouts, embedded within each page
- **JavaScript** — page interactions, language switching, navigation, food ordering, room-number handling, and WhatsApp integration
- **Google Fonts** — Cormorant Garamond, Great Vibes, and Montserrat
- **Font Awesome** — icons via CDN
- **localStorage** — language preference persistence
- No frameworks, build tools, or backend — fully static and deployable anywhere

## 🚀 Getting Started

No build steps needed — it's static HTML.

1. Clone the repository:
   ```bash
   git clone https://github.com/YASHWANTH0590/Hotel-ss.git
   ```
2. Open `index.html` in your browser, or serve the folder with any static file host.
3. Optional: append `?room=101` to `home.html`/`support.html` URLs to auto-fill the guest's room number (as done via the in-room QR code).

## 👥 Team

This was a freelance project built for a real hotel client, **SS Grand Inn, Samarlakota**.

### Yashwanth — Developer
Designed and developed the initial guest portal and core functionality, including:
- Overall website structure and page organization
- Home, Food, WiFi, Support, Explore, and Info pages
- Page styling and visual design
- Bilingual English/Telugu interface
- Food ordering flow and order summary
- WhatsApp-based food ordering and guest support integration
- Responsive, mobile-first guest experience
- Core JavaScript interactions and functionality
- Integration of hotel branding, images, icons, and page-level UI elements

### Puja Sri Mandadi — Developer
Contributed during the refinement and debugging stages to improve the project:
- Fixed the broken Back navigation on the WiFi page
- Identified and fixed broken absolute file paths for navigation links and logo images
- Applied navigation and asset-path corrections across `home.html`, `food.html`, `wifi.html`, `info.html`, `explore.html`, and `support.html`
- Added SEO meta descriptions across the guest portal pages
- Corrected the location-name inconsistency from **Samalkot** to **Samarlakota**
- Documented the project and contributor responsibilities in the README

## 📱 Guest Experience

The intended guest journey is:

```text
Room QR Code
     ↓
Welcome / Landing Page
     ↓
Guest Dashboard
     ↓
 ┌──────────────┬──────────────┬──────────────┐
 ↓              ↓              ↓
Food           WiFi          Support
 ↓              ↓              ↓
Order         Connect       Request Help
     ↓
Explore Nearby Places
     ↓
View Hotel Information
```

The portal provides guests with a single digital interface for accessing commonly required hotel services without installing a separate application.

## 🍽️ Digital Food Ordering

The food section provides guests with a digital in-room dining menu. Guests can browse food categories, view menu items and prices, filter items by category, add items to an order, review the order summary, and send order details through WhatsApp — a convenient digital alternative to traditional paper-based room-service menus.

## 💬 Guest Support

The support section provides quick access to commonly requested hotel services:
- 🧹 Housekeeping
- 🍽️ Food
- 📶 WiFi
- 🛏️ Extra bedding
- 🚕 Taxi
- 🧺 Laundry

Support requests are communicated through WhatsApp along with the guest's room number.

## 🌐 Bilingual Interface

The portal supports **English** and **Telugu**, with a language toggle available throughout the guest experience. The selected language is stored using browser `localStorage`, so the preference persists while navigating between pages.

## 📱 Responsive Design

The website follows a mobile-first approach, since the primary use case is guests accessing the portal through smartphones after scanning a QR code — with responsive layouts, mobile-friendly navigation, touch-friendly controls, and consistent visual design across pages.

## 📂 Project Structure

```text
Hotel-ss/
│
├── Img/
│   └── Images and branding assets
│
├── index.html
├── home.html
├── food.html
├── wifi.html
├── support.html
├── explore.html
├── info.html
│
└── README.md
```

## 🔧 Deployment

This is a static website with no build process required — no backend server, database, framework, or package manager needed. It can be opened directly in a browser or deployed on any standard static web-hosting service.

## 📌 Project Context

This project was developed as a **freelance project for SS Grand Inn, Samarlakota, Andhra Pradesh**, to give hotel guests a convenient digital interface for accessing hotel information, ordering food, getting WiFi details, requesting assistance, exploring nearby attractions, and communicating with hotel staff — all through a QR-code-based experience.

## 📜 License

Built for freelance client use — **SS Grand Inn, Samarlakota**. All rights reserved by the project owners.
