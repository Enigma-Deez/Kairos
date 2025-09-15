# Developer Notes

## Setup Checklist
- [x] Next.js + Turbopack
- [x] TailwindCSS
- [ ] ShadCN UI installed
- [ ] PWA configured (`next-pwa`)
- [ ] IndexedDB setup
- [ ] Heatmap visualization
- [ ] AI reflection module (local/offline)

## Known Issues
- Turbopack crash on Windows (see `next-panic-*.log`)
- Duplicate lockfiles (`package-lock.json`) at root and project folder → clean this up

## Ideas
- Habit quick-input: keyboard shortcuts, swipe gestures on mobile
- AI habit reflection: “Did you complete X today?” → yes/no → summary trendline
- Humanity mode: configurable “skip days” that don’t count as failure
