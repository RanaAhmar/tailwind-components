# Premium Tailwind CSS Components 🎨⚡️

[![Sponsored by Stackaura](https://img.shields.io/badge/Sponsored_by-Stackaura_&_Ahmar_Hussain-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.stackaura.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://www.stackaura.com/)

A curated collection of pixel-perfect, fully responsive, and accessible UI components built entirely with Tailwind CSS. Drop these into your React, Vue, or HTML projects to instantly elevate your design.

---

<div align="center">
  <h3>Sponsored by <a href="https://www.stackaura.com/">Stackaura</a> & Ahmar Hussain</h3>
  <p>Providing top-tier digital experiences and beautiful UI architectures.</p>
  <a href="https://www.stackaura.com/"><img src="https://img.shields.io/badge/Discover_Stackaura-Black?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Discover Stackaura" /></a>
</div>

---

## 🔥 Why this collection?

While there are many component libraries out there, most force you to install heavy NPM packages or lock you into a specific framework. 

**This repository only contains RAW HTML + Tailwind utility classes.**

- **Zero dependencies:** No `npm install`, no bloat.
- **Framework agnostic:** Works with Next.js, Nuxt, Laravel, Django, or plain HTML.
- **Accessible (a11y):** Built with WAI-ARIA guidelines in mind.
- **Dark Mode ready:** Every component includes `dark:` variants by default.

## 📦 What's Included?

Check the `/components` folder for categorized snippets:

### 1. Navigations & Footers
- Mega menus with animated dropdowns
- Glassmorphic sticky headers
- Fat footers with newsletter opt-ins

### 2. Marketing Sections
- High-converting hero sections
- Animated feature grids (using `group-hover` and `transition`)
- Pricing tables with toggle switches

### 3. Application UI
- Data tables with sticky headers
- Modals, sidebars, and slide-overs
- Form layouts with validation states

## 💻 Example: Glassmorphic Card

```html
<div class="relative w-full max-w-sm rounded-2xl border border-white/20 bg-white/10 p-8 shadow-2xl backdrop-blur-xl dark:border-white/10 dark:bg-black/20">
  <div class="absolute -top-4 -right-4 h-24 w-24 rounded-full bg-purple-500 blur-2xl opacity-50 mix-blend-screen"></div>
  <h3 class="relative text-2xl font-bold tracking-tight text-slate-900 dark:text-white">Premium Plan</h3>
  <p class="relative mt-4 text-slate-600 dark:text-slate-300">Unlock all features of our platform instantly.</p>
  <button class="relative mt-8 w-full rounded-xl bg-slate-900 px-4 py-3 font-semibold text-white transition-transform hover:scale-105 active:scale-95 dark:bg-white dark:text-black">Get Started</button>
</div>
```

## 🎨 Configuration Requirements

Ensure your `tailwind.config.js` is set up correctly. Specifically, some components rely on the default Tailwind color palette and spacing scale. Ensure `darkMode: 'class'` is enabled if you are using toggles.

## 🤝 Contributing

Have you built a beautiful component? We'd love to add it to the collection. Please read `CONTRIBUTING.md` before submitting a Pull Request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. You are free to use these components in commercial projects.

---
*Crafted with ❤️ by Ahmar Hussain and [Stackaura](https://www.stackaura.com/). Designing a better web.*


---

## 🚀 Discover More from Stackaura

If you found this tool useful, check out our other high-performance web utilities and follow **Ahmar Hussain** for more open-source excellence.

### 🌟 Featured Projects
- **[Free LLM APIs](https://github.com/RanaAhmar/free-llm-apis)** - A curated list of zero-cost AI endpoints.
- **[Awesome MCP Servers](https://github.com/RanaAhmar/awesome-mcp-servers)** - The ultimate collection of Model Context Protocol implementations.
- **[System Design Cheatsheet](https://github.com/RanaAhmar/system-design-cheatsheet)** - Master complex architectures in minutes.
- **[Next.js SaaS Starter](https://github.com/RanaAhmar/nextjs-saas-starter)** - The fastest way to launch your next product.

### 🔗 Stay Connected
- **Website:** [stackaura.com](https://www.stackaura.com/)
- **Author:** [Ahmar Hussain](https://github.com/RanaAhmar)

---
