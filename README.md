# Bai Fatima Andong — Portfolio

[![Live Site](https://img.shields.io/badge/live-fatimaandong.vercel.app-FF3B30?style=flat-square)](https://fatimaandong.vercel.app/)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![Deployed on Vercel](https://img.shields.io/badge/deployed%20on-Vercel-black?style=flat-square&logo=vercel)](https://vercel.com/)

Personal portfolio of **Bai Fatima Andong**, a Computer Science student at the University of Mindanao – Davao focused on AI and full-stack software development. Built to showcase projects, skills, and experience with a fast, modern, and distinctly branded interface.

**Live:** [fatimaandong.vercel.app](https://fatimaandong.vercel.app/)

## Overview

This site is a single-page portfolio with animated sections covering:

- **Hero** — intro, quick stats (projects, certifications, years coding), resume download
- **About** — bio, technical skills (Frontend / Backend / AI-ML / Tools), and a timeline of milestones
- **Projects** — filterable showcase (Machine Learning, Web Application, UI/UX Design) with live demo and source links, including an Android malware detection app and a diabetes prediction system
- **Certifications** — verified credentials (Databases, Network Security) with credential links
- **Contact** — direct email form plus quick links to email, GitHub, and LinkedIn
- **Recruiter Mode** — an in-site AI chat assistant for recruiters and visitors to ask questions about Fatima's background

## Tech Stack

- **Framework:** Next.js 15 (React)
- **UI:** MUI v9
- **Typography:** DM Sans, Instrument Serif, Syne, JetBrains Mono
- **Styling:** Custom red-accented brand/theme system
- **AI Integration:** Groq API (powers the Recruiter Mode chat assistant)
- **Email:** Resend API
- **Deployment:** Vercel

## Getting Started

```bash
git clone https://github.com/f4tm4ze/my-portfolio.git
cd my-portfolio
npm install
```

Create a `.env.local` file in the project root with the required keys:

```bash
GROQ_API_KEY=your_groq_api_key
RESEND_API_KEY=your_resend_api_key
```

> **Note:** `.env.local` is gitignored and should never be committed. If you're cloning this for reference, you'll need your own API keys from [Groq](https://console.groq.com/) and [Resend](https://resend.com/).

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it locally.

## Project Structure

```
my-portfolio/
├── app/              # Next.js app router pages
├── components/        # Hero, About, Skills, Projects, Timeline, Certifications, Contact, Stats
├── public/
│   └── images/        # Project thumbnails, logo, profile photo
└── styles/            # Theme and global styles
```

## Deployment

Deployed on [Vercel](https://vercel.com/). Pushes to `main` trigger automatic builds. Environment variables (`GROQ_API_KEY`, `RESEND_API_KEY`) must be set in the Vercel project settings, not just locally.

## Contact

- **GitHub:** [@f4tm4ze](https://github.com/f4tm4ze)
- **LinkedIn:** [Bai Fatima Andong](https://www.linkedin.com/in/bai-fatima-andong-330a05365)
- **Email:** baifatimaandong5@gmail.com

## License

This project is for personal portfolio use. Feel free to use it as inspiration, but please don't copy it wholesale as your own portfolio.
