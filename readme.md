# TOTC – E-Learning Landing Page

A pixel-perfect e-learning landing page built from a Figma design, converted into HTML/CSS at **1920px desktop width**, worked through section by section.

## 🚧 Project Status: In Progress

- ✅ Navbar (logo, nav links, login/signup buttons) — **Complete**
- ✅ Navbar responsive (mobile/tablet breakpoints) — **Complete**
- ✅ Hero section (curved background, two-tone heading, description, CTA buttons) — **Complete**
- ✅ Floating badge cards over hero image (stats badge, notification badge, class-schedule badge, chart badge) — **Complete**
- ✅ "Our Success" stats section (heading, description, 5-stat flex row with gradient numbers) — **Complete**
- ✅ "What is TOTC About" section — **Complete**
- ⏳ Remaining sections — **Not started yet**

Built section by section to match the Figma design as closely as possible, focusing on precise positioning, spacing, and typography.

## 📄 What's Built So Far

| Section | Details |
|---|---|
| **Navbar** | Logo (icon + text), 5 nav links, Login and Sign Up buttons, all flex-aligned; responsive with hamburger/collapse behavior on mobile and tablet breakpoints |
| **Hero section** | Curved teal background (`border-radius` on wrapper), two-tone heading (white + orange highlight text), description paragraph, "Join for free" button + custom play-button "Watch how it works" |
| **Hero image + badges** | Absolutely positioned floating cards on top of the hero image: <br>• Badge 1 – "250k Assisted Student" (calendar icon) <br>• Badge 2 – "Congratulations, admission completed" (email icon) <br>• Badge 3 – "User Experience Class" with tutor avatar, online status dot, and "Join Now" button <br>• Badge 4 – small chart icon badge |
| **Our Success stats section** | "Our Success" heading + description paragraph, 5-column stat row (15K+ Students, 75% Total success, 35 Main questions, 26 Chief experts, 16 Years of experience) with gradient (`from`/`to`) numbers using `bg-clip-text`, custom "Buenos Aires Trial" font, built with Tailwind CSS v4 |
| **What is TOTC About** | Section built with Tailwind CSS v4, matching Figma-specified spacing and typography |

## 🛠️ Built With

- HTML5 (semantic structure)
- Tailwind CSS v4 (CLI setup, utility-first styling, responsive breakpoints for navbar)
- CSS3 — Flexbox, absolute positioning for badge overlays, `backdrop-filter: blur()` for glassmorphism cards, gradient text via `bg-clip-text`
- Google Fonts — Poppins & Nunito Sans, custom font "Buenos Aires Trial"

## 📌 What's Left (Coming Next)

- Hero section responsiveness and remaining page sections (courses, features, testimonials, footer, etc. — as per Figma)
- Full responsive breakpoints across all sections (currently navbar only; rest fixed at 1920px desktop)
- Hover/active states for buttons and nav links
- Final cross-browser and pixel-diff check against Figma

## 📁 File Structure

```
├── index.html
├── styles.css
├── input.css / output.css (Tailwind)
├── package.json
├── Polygon-logo.svg
├── girl-image.png
├── calendar.svg / email.svg / chart.svg
└── README.md
```

## 🎯 Purpose

Practicing pixel-perfect conversion of a Figma design into clean, well-structured HTML/CSS (and Tailwind CSS) — focusing on precise measurements, layered/absolute positioning, and matching typography exactly to spec.

---
*Last updated: Navbar (with responsive behavior) + Hero section (with floating badges) + "Our Success" stats section + "What is TOTC About" section complete. Remaining sections to follow.*
