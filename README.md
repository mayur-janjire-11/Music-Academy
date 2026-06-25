# Music Next.js

Music Next.js is a music learning website built with Next.js, React, TypeScript, Tailwind CSS, and Framer Motion.

The project includes a home page with animated sections for courses, testimonials, webinars, instructors, and a course catalog page that uses local course data from `src/data/music_courses.json`.

## Aceternity UI Animations

This project uses Aceternity UI-style components for different animations and effects. The animated components are kept locally inside `src/components/ui`, including effects like spotlight, moving border, 3D cards, sticky scroll reveal, infinite moving cards, background gradients, hover cards, and animated tooltips.

To support these animations, the project uses:

- `framer-motion`
- `clsx`
- `tailwind-merge`
- `mini-svg-data-uri`
- `simplex-noise`
- `tailwindcss`

These packages are already listed in `package.json`, so running `npm install` will install everything needed.

If you want to install the animation dependencies manually, use:

```bash
npm install framer-motion clsx tailwind-merge mini-svg-data-uri simplex-noise
```

## How to Run

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open this URL in your browser:

```txt
http://localhost:3000
```


