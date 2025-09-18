## Tailwind CSS Practice

Hands-on Tailwind CSS practice based on the Scrimba Learn Tailwind CSS course. Focuses on utility-first classes, responsive design, and small UI patterns using the Tailwind CDN build.

### Live demo

- If deployed, add your URL here: https://your-deployment-url.example
- Local preview: open `index.html` directly or run with a lightweight server.

- Course: https://scrimba.com/learn-tailwind-css-c010:about
- Purpose: Practice Tailwind utility classes, responsive layouts, cards, and basic UI components.

### What’s here

- `index.html` uses Tailwind via the CDN (`<script src="https://cdn.tailwindcss.com"></script>`)
- Static assets in `img/`

### Features

- Responsive header and blog grid
- Reusable “card” layout with image, author, title, excerpt, and footer
- Hover states and subtle shadows for interactivity
- Simple newsletter form in the footer

### Run locally

- Open `index.html` directly in your browser, or
- Use a local server (e.g., VS Code Live Server/Five Server) to auto-reload while editing.

### Project structure

```
.
├── plant-blog-challenge/
│   ├── index.html     # Plant Blog page
│   └── img/           # Images for posts and authors
├── pomodoro-app-challenge/
└── README.md
```

### Tech stack

- HTML
- Tailwind CSS (CDN)

### Challenges

First link works now; the rest will work once you add the files at the repo root:

- Plant Blog Challenge — `plant-blog-challenge/index.html` → [Open](https://ajkendal.github.io/tailwind-work/plant-blog-challenge)
- Pomodoro App Challenge — `pomodoro-app-challenge/index.html` → [Open](https://ajkendal.github.io/tailwind-work/pomodoro-app-challenge)
- Testimonials Section Challenge — `testimonial-section-challenge/index.html` → [Open](https://ajkendal.github.io/tailwind-work/testimonial-section-challenge)
- Pricing Table Challenge — `pricing-table-challenge/index.html` → [Open](https://ajkendal.github.io/tailwind-work/pricing-table-challenge)
- Preferences Form Challenge — `preferences-form-challenge/index.html` → [Open](https://ajkendal.github.io/tailwind-work/preferences-form-challenge)
- 404 Page Layout Challenge — `404.html` → [Open](./404.html)

Feel free to keep all pages in the root for simplicity, or create a `pages/` folder and update the links accordingly.

### Accessibility and semantics

- Uses semantic HTML sections (`header`, `main`, `section`, `footer`)
- All images include `alt` text
- Color contrast and focus states rely on Tailwind defaults; can be tuned further if needed

### Author

- Your Name — add your preferred links (GitHub, LinkedIn, Portfolio)

### License

- MIT (or your preferred license). Add a `LICENSE` file if you plan to share/reuse.
