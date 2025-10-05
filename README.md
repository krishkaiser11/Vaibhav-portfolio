# Portfolio Website

A personal portfolio project built with [Next.js](https://nextjs.org/) and [Tailwind CSS](https://tailwindcss.com/). The site highlights a developer’s work, services, and skills with a modern layout. It includes custom fonts, theming support, and a component-based structure.

---

## Techniques of Interest

* **[App Router](https://nextjs.org/docs/app)** in Next.js for organizing pages and layouts.
* **[Custom Fonts with next/font](https://nextjs.org/docs/app/building-your-application/optimizing/fonts)** for optimized Google Fonts loading. Fonts include:

  * [Outfit](https://fonts.google.com/specimen/Outfit) (sans-serif)
  * [Ovo](https://fonts.google.com/specimen/Ovo) (serif)
* **[Tailwind theme extension](https://tailwindcss.com/docs/theme#extending-the-default-theme)** to define project-specific colors and font families.
* **CSS variables** declared in [`globals.css`](./app/globals.css) for theme customization.
* **[Framer Motion](https://www.framer.com/motion/)** for animations and smooth transitions.
* **Component modularization**: reusable UI elements such as `Navbar`, `Footer`, and `Work` are defined in the [components](./app/components/) directory.

---

## Libraries and Technologies

* [Next.js](https://nextjs.org/) – React framework for production.
* [Tailwind CSS](https://tailwindcss.com/) – utility-first styling.
* [Framer Motion](https://www.framer.com/motion/) – animation library.
* [Google Fonts](https://fonts.google.com/) – Outfit and Ovo included via `next/font`.

---

## Project Structure

```bash
portfolio/
├── app/
│   ├── components/        # Core UI sections: Navbar, About, Services, Work, etc.
│   ├── globals.css        # Tailwind and CSS variables
│   ├── layout.js          # Root layout, global metadata, fonts
│   └── page.js            # Main homepage
├── assets/                # Local images and asset data (infoList, workData, etc.)
├── public/                # Public static files (favicons, static images)
├── tailwind.config.mjs    # Tailwind configuration
├── postcss.config.mjs     # PostCSS configuration
├── package.json           # Project dependencies and scripts
└── README.md              # Documentation
```

**Interesting directories**

* **[`app/components/`](./app/components/)**: Contains modular React components for each site section.
* **[`assets/`](./assets/)**: Centralized file for content configuration, including projects, services, and skills.
