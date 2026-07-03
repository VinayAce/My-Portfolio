# Vinay Reddy Portfolio

Premium personal portfolio website for Vinay Reddy, built with Astro, Tailwind CSS, HTML-style Astro components, and minimal JavaScript.

## Tech Stack

- Astro
- Tailwind CSS
- HTML-style `.astro` components
- Minimal inline JavaScript for theme toggle and scroll reveal

## Project Structure

```text
src/pages/index.astro
src/components/
src/layouts/
src/styles/
public/images/
public/resume/
```

## Resume Download

Copy the resume PDF into:

```text
public/resume/Vinay_Reddy_Resume.pdf
```

The website download buttons use this path:

```text
/resume/Vinay_Reddy_Resume.pdf
```

## Setup

```bash
npm install
npm run dev
```

Open the local URL shown by Astro, usually:

```text
http://localhost:4321
```

## Build

```bash
npm run build
npm run preview
```

## Deployment

This site is static and can be deployed to Vercel, Netlify, Cloudflare Pages, GitHub Pages, or any static hosting provider.

For most platforms:

- Build command: `npm run build`
- Output directory: `dist`

## Notes

- No backend, database, authentication, Docker, Express, MongoDB, FastAPI, or unnecessary APIs are used.
- The project content is based on the uploaded resume and avoids confidential startup details.
