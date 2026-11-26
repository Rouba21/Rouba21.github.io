# Rouba Souidi — Interactive Portfolio

**Live site: [rouba21.github.io](https://rouba21.github.io)**

My personal portfolio, with an animated introduction and **Rouba**, a virtual assistant that answers questions about my background in French or English.

## Features

- Animated hero with my illustration, a typing intro and rotating greetings
- **Rouba chatbot**: answers questions about my experience, projects, skills, education, leadership, hobbies and availability
- **FR / EN** language switch (also detected from the browser, or forced with `?lang=en`)
- Tabbed experience timeline, project cards, skills, certifications, volunteering, hobbies
- Scroll animations, animated counters, rotating quotes
- Responsive layout for mobile

## Tech

Plain HTML, CSS and JavaScript in a single `index.html`, with no framework, no build step and no backend. The chatbot is a client-side keyword matcher over a small bilingual knowledge base, so it needs no API key.

## Useful links

| Link | Effect |
|---|---|
| `https://rouba21.github.io/?lang=en` | Opens the site in English |
| `https://rouba21.github.io/?chat=1` | Opens the site with the chat already open |
| `https://rouba21.github.io/?q=Projects` | Opens the chat and asks the question directly |

## Run locally

```bash
git clone https://github.com/Rouba21/Rouba21.github.io.git
cd Rouba21.github.io
# open index.html in a browser, or serve it:
python3 -m http.server 8000
```

## Files

| File | Role |
|---|---|
| `index.html` | The whole site: content, styles, animations and chatbot |
| `rouba.jpg` | Illustration used in the hero |
| `rouba-face.jpg` | Avatar used by the chatbot |

---

Contact: [roubasouidi.pro@gmail.com](mailto:roubasouidi.pro@gmail.com) · [LinkedIn](https://linkedin.com/in/rouba-souidi-20062001rs)
