# Kairos

Kairos is a **habit-tracking and productivity platform** inspired by GitHub’s contribution graph, the Life of Discipline app, and concepts from *Atomic Habits* (James Clear), Alex Hormozi, and Naval Ravikant — blended with Christian values and a focus on balance, rest, and sustainable growth.

## ✨ Features (Planned V1)
- Offline-first (works without internet, via PWA and IndexedDB)
- “Humanity mode” → account for mistakes, vacations, and missed days without breaking streaks
- Habit dashboard with heatmap visualization
- Blog/journaling space for reflections
- Quick input for habits (unique UI for fast check-ins)
- Mobile-first responsive design
- AI-assisted habit reflection (offline-capable, lightweight, bounded to avoid overuse)

## 📂 Project Structure
- `src/app/` → Next.js App Router pages (Dashboard, Habit Management, Settings)
- `src/components/` → UI components (ShadCN UI, Lucide icons, etc.)
- `public/` → static assets, PWA service worker
- `docs/` → extra documentation, design feedback, planning notes

## 🚀 Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/kairos.git
   cd kairos
2. Install dependencies:

npm install


Run the dev server:

npm run dev


Open http://localhost:3000

🛠️ Tech Stack

Next.js
 (App Router, Turbopack)

React

TailwindCSS

ShadCN UI

Lucide React

react-calendar-heatmap

IndexedDB
 (offline storage)

next-pwa
 (PWA support)

📝 License

Currently private. Will decide open-source license before public release.


---

Use this file to keep track of external feedback (friends, peers, testers).
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
