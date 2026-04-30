# imnotjef.dev

Personal portfolio built with Next.js, Tailwind, and Framer Motion using AI-assisted vibe coding.

[![Live Demo](https://img.shields.io/badge/Live%20at-imnotjef.vercel.app-000000?style=flat&logo=vercel&logoColor=white)](https://imnotjef.vercel.app)

---

## Overview

This is a developer portfolio designed to function as both a personal brand page and a technical showcase. It was built entirely through **vibe coding** — an AI-assisted development approach where the developer guides AI tools to generate, iterate, and refine code instead of writing every line manually.

The goal was direct: ship something real fast, learn the stack in the process, and have a public artifact to show while still at the beginning of the career. No overengineering, no tutorial-driven bloat — just a focused, functional portfolio.

---

## The Idea

The design came from studying what makes a developer portfolio actually work: clear identity, visible tech stack, real projects, honesty about current level, and frictionless navigation.

Two references shaped the visual direction:

- **[Klaus Portfolio](https://klaus-portfolio.vercel.app/)** — terminal aesthetic, monospace typography, ASCII borders, uppercase layout, brutalist minimalism
- **[Yohanan Design](https://yohanan.design/)** — dark background with breathing room, clean section separation, editorial feel

The result is a fusion: terminal details with editorial spacing. No noise, no gimmicks.

---

## AI Tools Used

**[Lovable.dev](https://lovable.dev/)** — main vibe coding tool. Used to generate the initial component structure, iterate on the UI based on prompts, and export clean React code. Lovable works best with specific, visual prompts written in English. Vague prompts produce vague results.

**[Claude](https://claude.ai/) (Anthropic)** — used as a senior engineering mentor throughout the project. Helped define the portfolio structure, write the design prompt for Lovable, decide which sections to include, and review every decision. Not used to write code directly, but to think through architecture and content strategy.

**[GitHub Copilot](https://github.com/features/copilot)** — used for autocomplete and this README generation.

---

## What Makes a Good Developer Portfolio

An opinionated technical breakdown of what actually matters:

- **Clear identity above the fold.** Name, role, one sentence — done. No animations that block information on first load.
- **Tech stack visibility.** Grouped by category (languages, frameworks, databases, tools). Recruiters scan this in 10 seconds — make it scannable.
- **Real projects only.** No tutorial clones, no Todo apps unless they demonstrate something specific. Each project needs: what it does, what problem it solves, what stack was used.
- **Honest level indicator.** Showing you are a beginner who is structured and moving fast is better than pretending to be a senior. Recruiters respect honesty.
- **Contact that works.** One email, one GitHub, one LinkedIn. That is it.
- **Performance.** Fast load, no bloat. A portfolio that takes 4 seconds to load kills credibility.
- **Mobile.** Non-negotiable. Most recruiters open links on mobile first.

---

## Project Structure

```
portfolio/
├── app/
│   ├── page.tsx         # Main page
│   └── layout.tsx       # Root layout, fonts, metadata
├── components/
│   ├── Hero.tsx
│   ├── About.tsx
│   ├── Stack.tsx
│   ├── Projects.tsx
│   ├── Contact.tsx
│   └── Cursor.tsx
├── public/
│   └── projects/        # Project screenshots
├── tailwind.config.ts
└── README.md
```

---

## How to Run Locally

```bash
# Clone the repository
git clone https://github.com/imnotjef/portfolio.git
cd portfolio

# Install dependencies
npm install

# Run dev server
npm run dev

# Open in browser
# http://localhost:3000
```

---

## Deploy

Deployed on **Vercel**. Any push to `main` triggers an automatic deploy.

Steps to deploy your own:

1. Connect the GitHub repository on [vercel.com](https://vercel.com)
2. Select the **Next.js** preset
3. Deploy. Done.

---

## What I Learned Building This

- **Vibe coding is a real skill.** Prompting well is harder than it looks. Vague prompts produce vague results.
- **Design decisions take longer than code.** Defining what NOT to include was the hardest part.
- **Framer Motion has a learning curve** even when you are not writing it by hand — understanding what the AI generated required reading the docs.
- **Shipping something imperfect and real is better than waiting for perfect.** This portfolio will evolve.
- **AI tools do not replace understanding.** You still need to know enough to review, correct, and direct what gets generated.

---

## Roadmap

- [ ] Add real project screenshots
- [ ] Connect contact form to email service
- [ ] Add CV download (PDF)
- [ ] Add dark/light toggle
- [ ] Translate to Portuguese (pt-BR)
- [ ] Add more projects as they are completed

---

## Author

**Jeferson** — Backend Engineer in progress

[github.com/imnotjef](https://github.com/imnotjef)

*"Do Zero ao Engenheiro de Software"*

---

## License

[MIT](LICENSE)
