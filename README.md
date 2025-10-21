# ThreadSure Ltd® - Multi-Page Business Website

A high-quality, modern, static multi-page business website for ThreadSure Ltd®, built with plain HTML + Tailwind CSS 3. No build step required.

## 🚀 Quick Start

1. **Open in Browser**: Simply open `index.html` in your web browser or host on any static hosting service.
2. **Static Hosting Options**:
   - Netlify (recommended for forms)
   - GitHub Pages
   - NHS server or any static host

## 📁 File Structure

```
threadsure-website/
├── index.html              # Home page (hero, mission, user journey, testimonials, press, demo CTA)
├── about.html              # Story, vision, values, NHS partnership banner
├── compliance.html         # GDPR, DTAC, WCAG 2.2, EU MDR, data-hosting badges
├── partners.html           # NHS trusts, MoJ, community services, EU clinics, collaboration form
├── press.html              # Media kit, downloadable logos, recent coverage, press@threadsure.co.uk
├── contact.html            # Departmental emails, WCAG-compliant form, Google-map embed (UK HQ)
├── privacy.html            # GDPR-compliant privacy policy
├── terms.html              # Terms of service
├── header.html             # Reusable header component
├── footer.html             # Reusable footer component
├── robots.txt              # SEO robots file
├── sitemap.xml             # XML sitemap for search engines
└── img/badges/             # Directory for compliance badges (placeholders)
```

## 🎨 Design Features

- **Mobile-First**: Responsive design that works on all devices
- **Accessibility**: WCAG 2.2 AA compliant with keyboard navigation, screen reader support, and high contrast
- **Performance**: Lazy-loaded images, pre-connected fonts, optimized for <3s load times
- **SEO**: Unique titles/meta descriptions, OG/Twitter cards, JSON-LD schema, hreflang for multi-language

## 🔧 Customization

### Replace Placeholder Logo
1. Replace the SVG in `header.html` with your actual ThreadSure logo
2. Update image paths in compliance badges section

### Update Contact Information
- Edit email addresses in `contact.html` and `footer.html`
- Update address and phone in `contact.html`
- Replace Google Maps embed with actual location

### Forms
- Contact forms use Formspree.io (replace `your-form-id` with actual Formspree form ID)
- Newsletter uses Mailchimp-ready class (update action URL)

### Colors & Branding
- NHS-style blues defined in Tailwind config
- Easy to modify in `header.html` Tailwind config

## 📊 SEO & Schema

- **JSON-LD**: Organization, Product, and FAQPage schemas included
- **Meta Tags**: Open Graph and Twitter Cards for social sharing
- **Hreflang**: Ready for EN/DE/FR language versions
- **Sitemap**: Static XML sitemap for search engines

## 🛡️ Compliance & Security

- **GDPR Ready**: Privacy policy and cookie notices
- **WCAG 2.2 AA**: Color contrast ≥4.5:1, focus indicators, ARIA labels
- **DTAC Compliant**: NHS Digital Technology Assessment Criteria ready
- **Data Hosting**: UK sovereign data centers mentioned

## 📈 Performance

- **Tailwind CDN**: No build step, instant loading
- **Lazy Loading**: Images load on demand
- **Font Optimization**: Pre-connected Google Fonts
- **Minimal JS**: Only essential interactivity

## 🌍 Multi-Language Ready

- Hreflang tags prepared for EN/DE/FR
- Language switcher stub in navigation
- Easy to duplicate pages for translations

## 📞 Support

For customization or deployment help:
- Email: support@threadsure.co.uk
- Press: press@threadsure.co.uk

---

**ThreadSure Ltd®** - Connecting Care. Empowering Recovery.