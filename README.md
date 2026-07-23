# GitBranch — Version Control from Scratch to Advanced

A free, multi-page educational website teaching version control (Git/GitHub) from beginner to advanced. Stripe-inspired design with animated terminal, scroll-reveal sections, and a comprehensive commands reference.

## What's Inside

| Chapter | Topic | Level |
|---|---|---|
| Home | Hero, animated terminal, chapter overview | — |
| Ch 1 | Introduction to Version Control | Beginner |
| Ch 2 | Core Concepts | Beginner |
| Ch 3 | Workflow & Mobile Dev | Intermediate |
| Ch 4 | Git Commands Reference | All Levels |
| Ch 5 | Advanced Git | Advanced |
| Ch 6 | Team Strategies & CI/CD | Advanced |
| Quiz | Test Your Knowledge | All Levels |

## How to Use

1. Open `index.html` in any browser — no server needed
2. Follow chapters in order, or jump to what you need
3. Use the prev/next navigation at the bottom of each page
4. Copy code snippets from the cheat sheet into your terminal
5. Click resource links to go deeper
6. Take the quiz to test your knowledge

## File Structure

```
├── index.html      # Landing page with hero and chapter cards
├── styles.css      # Shared CSS (all design and animations)
├── script.js       # Shared JS (scroll-reveal)
├── chapter1.html   # Introduction to Version Control
├── chapter2.html   # Core Concepts
├── chapter3.html   # Workflow & Mobile Dev
├── chapter4.html   # Git Commands Reference
├── chapter5.html   # Advanced Git
├── chapter6.html   # Team Strategies & CI/CD
├── quiz.html       # Interactive quiz with scoring
└── README.md       # This file
```

## How to Customize

- **Colors:** change CSS variables in `styles.css` (`:root` section)
- **Content:** edit text directly in each chapter's HTML file
- **Chapters:** add/remove HTML files and update navigation links
- **Terminal:** edit the `.terminal-body` div in `index.html`
- **Resources:** update hrefs and descriptions in chapter files

## Tech Stack

- HTML5, CSS3 (custom properties, grid, flexbox, animations, backdrop-filter)
- Vanilla JS (IntersectionObserver for scroll-reveal, no frameworks)
- Google Fonts (Inter + JetBrains Mono)

## Browser Support

All modern browsers. Uses `prefers-reduced-motion` for accessibility.

## License

Free to use, modify, and share. Built for learning.
