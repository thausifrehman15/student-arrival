# Budapest Arrival — VIP Student Relocation & Concierge

An ultra-luxury editorial travel magazine styled service booking website designed for South Asian scholars transitioning to Budapest, Hungary.

Built with pure, self-contained static web technologies:
- **GSAP 3 & ScrollTrigger**: Multi-depth physics-based parallax scrolling (Danube River, Chain Bridge, and Parliament skyline).
- **Split-Screen Hero**: High-fashion typography paired with an interactive live "Budapest Concierge OS" Student Dashboard mockup.
- **Horizontal Onboarding Timeline**: Scroll-driven animated liquid gold path.
- **Asymmetrical Bento Grid**: Core relocation services with glassmorphic lift and soft metallic gold sheen.
- **3-Tier Concierge Pricing Table**: Budapest Essential, The Academic Elite (Featured), and The Royal Transition with instant currency conversion (EUR / HUF).
- **Multi-Step Booking Wizard (Amelia / LatePoint Pro Style)**: 4-step intake engine with real-time price calculation, zero-backend submission (FormSubmit.co / Web3Forms), boarding-pass style receipt, and instant 1-click WhatsApp concierge dispatch.

## 🚀 Instant Deployment (GitHub Pages)

This repository is **100% static** with **zero backend server required**.

1. Go to your GitHub Repository Settings: `Settings > Pages`.
2. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`), folder: `/ (root)`
3. Click **Save**. Within 1–2 minutes, your website is live at:
   `https://<your-username>.github.io/student-arrival/`

## ⚙️ Configuration (Email & WhatsApp)

Open `student-arrival.html` (and `index.html`), scroll to the bottom `<script>` block, and configure your details:

```javascript
const CONCIERGE_CONFIG = {
  // Enter the email address where you want to receive booking inquiries (free FormSubmit service)
  notificationEmail: 'concierge@budapestarrival.com',

  // Your agency WhatsApp phone number (country code without '+' e.g. 36301234567)
  whatsAppNumber: '36301234567',

  // Optional: Custom Webhook / Google Form URL
  formServiceUrl: 'https://formsubmit.co/ajax/'
};
```

© 2024 Budapest Arrival Concierge. Designed for South Asian Students in Budapest, Hungary.

