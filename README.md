
All styles and scripts are embedded within `index.html` for easy deployment and portability.

## 🚀 Getting Started

### Local Viewing

1. Clone or download the repository.
2. Open `index.html` directly in your preferred web browser.

No build tools or server are required – it runs entirely client‑side.

### Deployment

Because this is a static HTML file, you can host it on any web server or platform like:

- GitHub Pages
- Netlify
- Vercel
- Any shared hosting service

## 🧩 Key Sections

| Section ID      | Description |
|-----------------|-------------|
| `#about`        | Programme description and learning objectives |
| `#overview`     | Credit distribution and programme statistics |
| `#curriculum`   | Tabbed interface for all semester courses |
| `#structure`    | Timeline visualisation of the four‑year journey |
| `#search-section` | Live course search with real‑time filtering |

## 🔍 Search Functionality

The search input filters through all 35+ courses across eight semesters. Matches are case‑insensitive and can be based on:

- Course code (e.g., `ASF 1101`)
- Course name (e.g., `Biochemistry`)

Each result displays the course code, full name, type (Compulsory/Optional), and the semester.

## ♿ Accessibility Features

- **Skip Link** – Allows keyboard users to bypass navigation
- **ARIA Roles & Properties** – Properly labelled tabs, search live region
- **Focus Indicators** – Visible outline for keyboard navigation
- **Semantic Headings** – Logical document outline
- **Responsive Tables** – Scrollable containers with `overflow-x: auto`

## 📱 Responsive Behaviour

- At widths below `700px`:
  - About grid stacks to a single column
  - Navigation bar scrolls horizontally
  - Timeline adapts to narrower column layout
- Tables within the curriculum section become horizontally scrollable rather than breaking layout

## 🎨 Design System

The colour palette is inspired by nature and academia:

| Variable       | Hex       | Usage |
|----------------|-----------|-------|
| `--forest`     | `#1a3a2a` | Primary background, headings |
| `--moss`       | `#2d5a3d` | Hover states, secondary elements |
| `--leaf`       | `#4a8c5c` | Buttons, accents |
| `--sage`       | `#7ab893` | Highlight text, stats |
| `--cream`      | `#f5f0e8` | Main content background |
| `--sand`       | `#e8dfc8` | Alternate section background |

Typography combines the elegant **Playfair Display** for titles with the clean **DM Sans** for body text, and **DM Mono** for technical labels and codes.

## 📝 Data Source

All course information is sourced from the official curriculum of the Faculty of Agriculture, University of Peradeniya. The data is stored as a JavaScript array within the page for easy maintenance and updates.

## 🤝 Contributing

If you notice any discrepancies in course details or would like to suggest improvements:

1. Fork the repository
2. Update the `SEMESTERS` array in the `<script>` section
3. Submit a pull request with a clear description of your changes

## 📄 License

This project is intended for educational and informational purposes. Feel free to adapt it for similar programme showcases with appropriate attribution.

---

**Built for the Faculty of Agriculture, University of Peradeniya**  
*Designed & Developed by IHAN INDEEPA*