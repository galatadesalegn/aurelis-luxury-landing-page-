<div align="center">

# 🚀 Auxiliary

### Modern, High-Converting Landing Page

[![React](https://img.shields.io/badge/React-18.x-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-11.x-0055FF?style=flat-square&logo=framer&logoColor=white)](https://www.framer.com/motion)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Deploy](https://img.shields.io/badge/live-online-brightgreen?style=flat-square)](https://your-live-url.com)

<br/>

> A sleek, animated, and fully responsive landing page built to convert visitors into customers. Fast, accessible, and easy to customize.

<br/>

**[🌐 Live Demo](https://your-live-url.com)** · **[🐛 Report Bug](https://github.com/galatadesalegn/auxiliary/issues)** · **[✨ Request Feature](https://github.com/galatadesalegn/auxiliary/issues)**

</div>

---

## ✨ Features

- 🎞️ **Smooth animations** — scroll-triggered reveals with Framer Motion
- 📱 **Fully responsive** — pixel-perfect on mobile, tablet, and desktop
- 🌑 **Dark / Light mode** — system-aware with manual toggle
- ⚡ **Blazing fast** — Vite build, lazy-loaded images, optimized assets
- 📬 **Newsletter signup** — email capture with form validation
- ♿ **Accessible** — semantic HTML, ARIA labels, keyboard navigation
- 🔍 **SEO optimized** — Open Graph, Twitter Card, and meta tags
- 🧩 **Component-based** — every section is an isolated, reusable component

---

## 🛠 Tech Stack

| Technology | Purpose |
|-----------|---------|
| React 18 | UI framework |
| Tailwind CSS 3 | Styling |
| Vite 5 | Build tool & dev server |
| Framer Motion | Animations |
| Lucide React | Icons |
| React Hook Form | Form handling & validation |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18+
- npm or yarn

### 1. Clone the repo

```bash
git clone https://github.com/galatadesalegn/auxiliary.git
cd auxiliary
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the dev server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### 4. Build for production

```bash
npm run build
```

---

## 📁 Project Structure

```
auxiliary/
├── public/
│   ├── favicon.ico
│   └── og-image.png              # Open Graph preview image
├── src/
│   ├── components/
│   │   ├── Navbar.jsx             # Sticky nav with mobile menu
│   │   ├── Hero.jsx               # Hero section with CTA
│   │   ├── Features.jsx           # Feature highlights grid
│   │   ├── HowItWorks.jsx         # Step-by-step explainer
│   │   ├── Testimonials.jsx       # Customer quotes carousel
│   │   ├── Pricing.jsx            # Pricing tiers table
│   │   ├── FAQ.jsx                # Accordion FAQ section
│   │   ├── Newsletter.jsx         # Email capture form
│   │   └── Footer.jsx
│   ├── data/
│   │   ├── features.js            # ← Edit to update features
│   │   ├── testimonials.js        # ← Edit to update reviews
│   │   ├── pricing.js             # ← Edit to update pricing
│   │   └── faq.js                 # ← Edit to update FAQs
│   ├── hooks/
│   │   └── useScrollReveal.js
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── tailwind.config.js
├── vite.config.js
└── index.html
```

---

## 🗂 Page Sections

| Section | Description |
|---------|-------------|
| **Navbar** | Sticky header with logo, nav links, and CTA button |
| **Hero** | Bold headline, subtext, CTA buttons, and hero image |
| **Features** | Icon grid highlighting key product benefits |
| **How It Works** | Numbered step-by-step walkthrough |
| **Testimonials** | Customer reviews with avatars and star ratings |
| **Pricing** | Three-tier pricing cards with feature lists |
| **FAQ** | Collapsible accordion for common questions |
| **Newsletter** | Email signup with validation |
| **Footer** | Links, socials, and copyright |

---

## 🎨 Customization

All content is stored in `src/data/` — no need to touch component code.

**Update features** — `src/data/features.js`:

```js
export const features = [
  {
    icon: "Zap",              // any Lucide icon name
    title: "Lightning Fast",
    description: "Optimized for performance from day one.",
  },
];
```

**Update pricing** — `src/data/pricing.js`:

```js
export const plans = [
  {
    name: "Starter",
    price: "$9",
    period: "per month",
    features: ["5 projects", "10GB storage", "Email support"],
    highlighted: false,
  },
  {
    name: "Pro",
    price: "$29",
    period: "per month",
    features: ["Unlimited projects", "100GB storage", "Priority support"],
    highlighted: true,    // ← adds the "Most popular" badge
  },
];
```

**Change brand colors** — `tailwind.config.js`:

```js
theme: {
  extend: {
    colors: {
      primary: "#6C63FF",     // main brand color
      secondary: "#F5F3FF",   // light accent
    }
  }
}
```

---

## 🌍 Deployment

### Vercel (recommended)

```bash
npm run build
# Deploy /dist to Vercel
```

Or connect your GitHub repo to [Vercel](https://vercel.com) for automatic deploys on every push to `main`.

### Netlify

```bash
npm run build
# Drag and drop the /dist folder to Netlify Drop
# Or connect your GitHub repo for auto-deploys
```

---

## 📄 License

MIT — free to use, modify, and distribute. See [`LICENSE`](LICENSE).

---

<div align="center">

Built by **Galata Desalegn** — Addis Ababa, Ethiopia

⭐ Star this repo if you found it helpful!

</div>
