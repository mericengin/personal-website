# Kaya Meriç Engin — Personal Website

The personal portfolio and research archive of Kaya Meriç Engin, an ML Engineer and Computational Linguistics MSc student based in Stuttgart, Germany.

## Overview

This repository contains the source code for my personal website, built with [Astro](https://astro.build). It serves as a centralized hub for my:
- **Academic Research**: Investigations into LLM deductive reasoning, autonomous agents, and NLP applications.
- **Applied Engineering Work**: Case studies covering financial sentiment pipelines, RAG chatbots, and scalable Angular/NgRx frontend architecture. 

The design is typography-led, inspired by print media, and built to be lightweight, fast, and accessible.

## Tech Stack

- **Framework**: [Astro](https://astro.build) (Static Site Generation)
- **Styling**: Vanilla CSS with custom CSS variables
- **Typography**: Lora (Serif), Inter (Sans), JetBrains Mono (Monospace)
- **Deployment**: Designed for static hosting (GitHub Pages, Vercel, Netlify)

## Local Development

To run this project locally:

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Start the development server**
   ```bash
   npm run dev
   ```
   The site will be available at `http://localhost:4321`.

3. **Build for production**
   ```bash
   npm run build
   ```
   The production-ready static files will be generated in the `dist/` directory.

## Project Structure

```text
/
├── public/           # Static assets (favicons, etc.)
├── src/
│   ├── components/   # Reusable UI components (Nav, Footer)
│   ├── layouts/      # Global layout wrapper and CSS variables
│   └── pages/        # Astro routes (index, research, work)
└── astro.config.mjs  # Astro configuration
```

## Contact

You can reach me at [kayamericengin@gmail.com](mailto:kayamericengin@gmail.com) to discuss NLP/LLM research, AI product engineering, or game development.
