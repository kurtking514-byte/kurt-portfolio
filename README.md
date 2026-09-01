# Kurt Magastino | Portfolio

My personal portfolio website — hardware, robotics, and software projects, built with [Astro](https://astro.build) and [TailwindCSS](https://tailwindcss.com/).

Live site: [kurt-magastino.vercel.app](https://kurt-magastino.vercel.app)

## Tech Stack

- [Astro](https://astro.build)
- [TailwindCSS](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)

## Running locally

```
pnpm install
pnpm run dev
```

## Project Structure

```
├── src/
│   ├── components/
│   │   ├── cv/
│   │   │   ├── TimeLine
│   │   ├── BaseHead.astro
│   │   ├── Card.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── HorizontalCard.astro
│   │   └── SideBar.astro
│   │   └── SideBarMenu.astro
│   │   └── SideBarFooter.astro
│   ├── content/
│   │   ├── blog/
│   │   ├── store/
│   ├── layouts/
│   │   └── BaseLayout.astro
│   │   └── PostLayout.astro
│   └── pages/
│   │   ├── blog/
│   │   └── cv.astro
│   │   └── index.astro
│   │   └── projects.astro
│   │   └── rss.xml.js
│   ├── styles/
│   │   └── global.css
│   └── config.ts
├── public/
├── astro.config.mjs
├── tailwind.config.cjs
├── package.json
└── tsconfig.json
```

### Site config

Global site settings live in `src/config.ts` (site title, description, and a couple of feature flags).

### Deploy

Deployed on [Vercel](https://vercel.com). Pushing to `main` triggers a redeploy.

---

Built on top of the [Astrofy](https://github.com/manuelernestog/astrofy) template, originally created by [manuelernestog](https://github.com/manuelernestog) and licensed under MIT.
