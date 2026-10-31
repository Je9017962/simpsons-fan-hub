# The Simpsons Fan Hub

MMC5277: Web Design Principles, Fall 2026 · Group Project (Assignment 9)

**Team:** Jeremiah Morris-Wyley (leader, Home) · Tiffany Wilson (Characters) · Dahye Kim (Exhibition)

=
---

## Project structure

```
simpsons-fan-hub/
├── index.html        Home page          (Jeremiah)
├── page2.html        Character Guide    (Tiffany)
├── page3.html        Exhibition         (Dahye)
├── README.md
└── css/
    ├── style.css     SHARED: header, nav, footer, colors, cards, breakpoints
    ├── home.css      index.html only
    ├── page2.css     page2.html only
    └── page3.css     page3.html only
```

Every page loads `css/style.css` first, then its own page file.

---

## Team conventions

**BEM naming:** `.block`, `.block__element`, `.block--modifier`
- Shared blocks (don't rename): `header`, `nav`, `main`, `section`, `card`, `footer`
- Page blocks: use a name unique to your page (e.g. `.characters__item`, `.exhibit__date`)
- No styling by ID or bare tag names in page CSS files

**Colors and fonts:** use the variables in `style.css` (`var(--color-yellow)`, etc.) so all pages match.

**Breakpoints** (use these same two everywhere):
- Tablet: `@media (max-width: 768px)`
- Phone: `@media (max-width: 480px)`



