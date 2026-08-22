# 🐾 Pet Adoption

A responsive static website demonstrating a simple pet-adoption journey: learn about adoption, submit applicant details, choose a pet, make a demo donation pledge, contact the project, and view veterinary consultation information.

> **Demo notice:** This is a front-end student project. Forms use browser-side JavaScript/local storage only; no real adoption, payment, or medical booking is processed.

## ✨ Features

- Responsive navigation and layouts for desktop and mobile.
- Semantic HTML5 structure and accessible form labels.
- Keyboard-visible focus states and a skip-to-content link.
- Adoption applicant form with client-side validation.
- Pet and breed selection with exactly-one selection validation.
- Donation pledge demo that explicitly avoids collecting real payment credentials.
- Contact form demo with accessible status messages.
- Veterinary consultation cards with phone links.
- Shared CSS for consistent design and reduced duplication.

## 🛠️ Built With

- **HTML5** — semantic page structure and forms
- **CSS3** — responsive layout, grid, styling and accessibility states
- **Vanilla JavaScript** — validation, localStorage and demo interactions

## 📁 Project Structure

```text
.
├── index.html       # Home / landing page
├── project1.html    # Adoption information and applicant form
├── project2.html    # Pet and breed selection
├── project3.html    # Donation pledge demo
├── project4.html    # Contact form demo
├── project5.html    # Veterinary consultation information
├── style.css        # Shared responsive and accessible styles
├── dog2.jpg         # Home hero image
├── dog3.jpg         # Pet imagery
├── dogg.jpeg        # Dog card image
├── cat1.jpeg        # Cat card image
├── rabbit1.jpeg     # Rabbit card image
└── birds.jpeg       # Bird card image
```

The older `project*.css` files are retained for repository history/compatibility; the current pages use the shared `style.css`.

## 🚀 Run Locally

No build tools are required.

1. Clone the repository:
   ```bash
   git clone https://github.com/Naveen022004/Pet-adoption.git
   cd Pet-adoption
   ```
2. Open `index.html` in a browser, or use VS Code Live Server for local development.

## 🌐 GitHub Pages

Because the project is a static site with `index.html` at the repository root, it can be published directly with GitHub Pages using the `main` branch and `/ (root)` as the publishing source.

## ♿ Accessibility

The current pages include descriptive metadata, semantic headings, explicit form labels, keyboard focus indicators, `aria-current` navigation state, live status messages, descriptive image alternatives, and reduced-motion support.

## 📄 License

This project is intended for educational and portfolio use.