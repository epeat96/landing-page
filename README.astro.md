# Landing Page

This repository contains the source for a personal landing page built with [Astro](https://astro.build) and Tailwind CSS. It ships with the [Dracula](https://draculatheme.com/) color palette via the `tailwind-dracula` plugin, giving the site its distinctive dark theme. Use it as a starting point to introduce yourself or showcase a project.

## Project Structure

```
/
├── public/              # Static assets such as fonts and favicon
└── src/
    ├── components/     # Reusable Astro components
    ├── layouts/        # Page layouts
    └── pages/          # Route files (e.g. index.astro)
```

## Usage

- `npm install` – install dependencies
- `npm run dev` – start a development server at `http://localhost:4321`
- `npm run build` – build the production site into `dist/`
- `npm run preview` – preview the build locally
- The dark theme comes from the `tailwind-dracula` plugin defined in `tailwind.config.js`; adjust or remove it to use a different palette.

Customize the content by editing files in `src/pages` and `src/components`.

