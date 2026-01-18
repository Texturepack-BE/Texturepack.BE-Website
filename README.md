# TexturepackBE

> A modern Minecraft Bedrock texture pack gallery - Full-stack web application

[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?style=flat-square&logo=supabase)](https://supabase.com/)

**Live:** [https://texturepack.be](https://texturepack.be)

---

## About

TexturepackBE is a community platform where users can discover, download, and share Minecraft Bedrock Edition texture packs. The platform serves thousands of users looking for PvP packs, aesthetic packs, and other resource packs for Minecraft Bedrock.

---

## Features

- **Search & Discovery** - Full-text search with tag filters, resolution filters, and multiple sorting options
- **Pack Management** - Upload system with multi-image galleries and YouTube video integration
- **User Profiles** - Gamification with level system (Copper to Netherite) and community ranks
- **Authentication** - Discord OAuth integration for seamless login
- **SEO** - Server-side rendering with structured data for search engine visibility

---

## Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS 4 |
| **UI Components** | Radix UI, Framer Motion, Lucide Icons |
| **Backend** | Supabase (PostgreSQL, Auth, Realtime) |
| **Storage** | Cloudflare R2 |
| **Deployment** | Vercel with Analytics & Speed Insights |

---

## Architecture

```
src/
├── app/
│   ├── api/              # RESTful API endpoints
│   ├── pack/[slug]/      # Dynamic pack pages (SSR)
│   ├── user/[username]/  # User profile pages (SSR)
│   ├── search/           # Search with filters
│   └── upload/           # Pack upload flow
├── components/
│   ├── ui/               # Reusable UI primitives
│   └── [features]/       # Feature-specific components
├── hooks/                # Custom React hooks
└── lib/                  # Shared utilities
```

---

## Technical Highlights

- **Server Components** - Pack and user pages use SSR for SEO and performance
- **Custom Hooks** - Reusable logic for auth, search, data fetching
- **RESTful API** - Clean API layer with pagination, filtering, and sorting
- **Responsive Design** - Mobile-first approach with Tailwind breakpoints
- **Accessible UI** - Radix primitives for keyboard navigation and screen readers

---

## License

This repository contains documentation only. The source code is private.
