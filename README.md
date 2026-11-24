<h1 align="center">Ibrahim Naji Sharaf</h1>
<p align="center"><b>Frontend & Junior Full-Stack Developer</b> · React · TypeScript · Node.js · PostgreSQL</p>
<p align="center">Al Khobar, Saudi Arabia · Software Engineering graduate, Ural Federal University (2022–2026)</p>

<p align="center">
  <a href="mailto:hemo.n90@outlook.sa"><img src="https://img.shields.io/badge/Email-hemo.n90%40outlook.sa-0A66C2?style=flat-square&logo=maildotru&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Arabic-Native-2E7D32?style=flat-square" alt="Arabic: native">
  <img src="https://img.shields.io/badge/English-B2-1565C0?style=flat-square" alt="English: B2">
  <img src="https://img.shields.io/badge/Russian-B1-6A1B9A?style=flat-square" alt="Russian: B1">
</p>

---

I build **Arabic-first (RTL) and bilingual web applications** for real businesses: storefronts, ordering systems and the admin panels behind them. I work across the frontend, the API and the database, and I care about the details users and businesses notice, like correct prices, mobile layouts, fast pages and safe handling of data.

## Tech stack

**Frontend:** 
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)

**Backend & data:** 
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-555555?style=flat-square)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)

**Tools:** 
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

## Featured work

### 🍳 [Top Designs — kitchen catalogue & ordering platform](https://github.com/hemo-n90/top-designs-ordering-platform)
<a href="https://github.com/hemo-n90/top-designs-ordering-platform"><img src="https://raw.githubusercontent.com/hemo-n90/top-designs-ordering-platform/main/docs/screenshots/home-desktop.jpg" width="49%" alt="Top Designs home"></a>
<a href="https://github.com/hemo-n90/top-designs-ordering-platform"><img src="https://raw.githubusercontent.com/hemo-n90/top-designs-ordering-platform/main/docs/screenshots/admin-orders.jpg" width="49%" alt="Top Designs admin orders"></a>

A full-stack Arabic platform for a Saudi kitchen manufacturer: catalogue, pricing by the metre, cart, visit booking, an admin dashboard and WhatsApp notifications.
**React · TypeScript · Express · PostgreSQL · Drizzle · Twilio** · built with a teammate

- Built the request flows with WhatsApp delivery, the About/Contact pages and the admin order routes. Also fixed deployment problems: SPA fallback, upload storage and the proxy settings.
- Moved order pricing to the server and added tests. Before this, a modified request could save any price.
- Verified Twilio webhook signatures and got clean Linux builds and a passing typecheck.

### 🛋️ [Homeit — bilingual furniture e-commerce](https://github.com/hemo-n90/homeit-furniture-store)
<a href="https://github.com/hemo-n90/homeit-furniture-store"><img src="https://raw.githubusercontent.com/hemo-n90/homeit-furniture-store/main/docs/screenshots/home-ar-desktop.jpg" width="49%" alt="Homeit Arabic home"></a>
<a href="https://github.com/hemo-n90/homeit-furniture-store"><img src="https://raw.githubusercontent.com/hemo-n90/homeit-furniture-store/main/docs/screenshots/product-desktop.jpg" width="49%" alt="Homeit product page"></a>

An Arabic/English store with RTL and LTR layouts, a wishlist, cart, checkout and an admin panel. Built as a pnpm monorepo with an OpenAPI contract and generated typed clients.
**React 19 · TypeScript · Express 5 · PostgreSQL · Drizzle · OpenAPI**

- Generated with Replit Agent from my requirements, then reviewed and hardened by me:
  - transactional orders priced on the server in integer hundredths
  - upload checks based on file content, login rate limiting and refusal to start with a weak secret
- Fixed mobile and header layout bugs and replaced 26 third-party image hotlinks with bundled assets.

### 🍔 Grin Burger — restaurant ordering & staff dashboard *(team project, private client repository)*
A restaurant ordering app with a customer menu, cart, OTP sign-in and order tracking, plus a staff dashboard with five roles.
**Next.js 14 (App Router) · React · Express · Prisma · PostgreSQL · Turborepo · Playwright · Railway**

- 17 of the project's 24 commits are mine:
  - prepared the Railway deployment and the WhatsApp integration
  - moved customer OTP to Twilio Verify (SMS, then voice)
  - added a secure owner-creation script
  - built menu item descriptions, extra quantities and order notes
  - fixed dashboard stability and stale menu data

### 🪑 [AWJ Furniture — team contribution](https://github.com/ramynady78/alqattan)
A furniture catalogue with gallery and admin content workflows. I contributed the AWJ rebrand, gallery and image-upload fixes, accessibility and alert fixes, and the TikTok/WhatsApp settings across the frontend and the API schema.

### 🧃 [Top Juice — juice shop menu](https://github.com/hemo-n90/top-juice) · [live](https://top-juice.vercel.app)
<a href="https://top-juice.vercel.app"><img src="https://raw.githubusercontent.com/hemo-n90/top-juice/main/docs/screenshots/menu-desktop.jpg" width="49%" alt="Top Juice menu"></a>

An Arabic menu site built with vanilla JavaScript: search, image lightbox and mobile navigation. I cut the page's image payload from 146 MB to 11 MB and fixed the missing icons.

## How I work
- Changes go in small, reviewed pull requests, each with a clear description of what was tested.
- I verify behaviour against a real database and browser, not just a successful build.
- I use AI coding assistants as part of my workflow, and I review, test and take responsibility for what I ship.

## Contact
📧 [hemo.n90@outlook.sa](mailto:hemo.n90@outlook.sa) · 📍 Al Khobar, Saudi Arabia · Open to **Frontend, React, Software Engineer and Junior Full-Stack** roles.
