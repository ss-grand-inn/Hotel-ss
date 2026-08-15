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

- **HTML5** only — CSS and JavaScript are embedded within each page (GitHub language stats show 100% HTML for this reason)
- Google Fonts (Cormorant Garamond, Great Vibes, Montserrat) and Font Awesome icons via CDN
- No frameworks, build tools, or backend — fully static, deployable anywhere

## 🚀 Getting Started

No build steps needed — it's static HTML.

1. Clone the repository:
   ```bash
   git clone https://github.com/YASHWANTH0590/Hotel-ss.git
   ```
2. Open `index.html` in your browser, or serve the folder with any static file host.
3. Optional: append `?room=101` to `home.html`/`support.html` URLs to auto-fill the guest's room number (as done via the in-room QR code).

## 👥 Contributors

| Name | Contribution |
|------|--------------|
| Yashwantha | Initial project build — page structure, styling, and core functionality |
| [Your Name] | *(add your specific contribution here — e.g. Telugu translations, specific pages, food menu content, bug fixes, testing)* |

> Note: This was a freelance collaborative project. [Your Name] was added as a GitHub collaborator after initial development; contributions were made directly during the build process and reflected here.

## 📄 License

Built for freelance client use — SS Grand Inn, Samarlakota. All rights reserved by the project owners.
