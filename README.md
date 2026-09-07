# Emaan Mubashar — AI Engineer Portfolio Website

A single-page, dark-themed personal portfolio and CV website for "Emaan Mubashar", AI Engineer & Web Developer. Built on top of the BreezyCV template and fully customized with real profile content, AI-project portfolio cards, and custom SVG visuals.

## 🔗 Live Sections

The site is a one-page app with smooth scroll/animated navigation between:

- Home — Intro with animated title/subtitle rotation
- About Me — Bio, contact info, and "What I Do" services (Generative AI, Deep Learning, Machine Learning, LLM Systems, Web Development)
- Resume — Education, experience, and skill bars (Core Skills + AI/ML & GenAI Skills)
- Portfolio — AI project showcase, each linked directly to its GitHub repository
- Contact — Contact details, embedded map, and a message form

## ✨ Features

- Fully responsive, dark UI with purple accent theme
- Custom inline SVG project visualizations for each portfolio item (no external image dependencies)
- Font Awesome icons loaded via CDN (no local font files required)
- Direct GitHub links on every portfolio project
- Animated skill bars for core programming and AI/ML competencies
- Embedded Google Map for location
- Contact form (front-end markup; backend endpoint configurable)

## 🧠 Featured AI Projects

| Project | Description | Repository |
|---|---|---|
| Document RAG Agent | Retrieval-Augmented Generation over documents | [GitHub](https://github.com/Emaan-GH/Document-RAG-Agent) |
| AI Chatbot Project | Conversational AI chatbot | [GitHub](https://github.com/Emaan-GH/Ai-Chatbot-Project) |
| Support Pearls | AI-powered customer support assistant | [GitHub](https://github.com/Emaan-GH/Support-Pearls) |
| Medi Guide AI Assistant | Healthcare guidance AI assistant | [GitHub](https://github.com/Emaan-GH/Medi-Guide-ai-assistant) |
| Markz Mind | AI mind-mapping / knowledge tool | [GitHub](https://github.com/Emaan-GH/Markz-Mind) |
| Finwise AI | AI-powered finance assistant | [GitHub](https://github.com/Emaan-GH/Finwise_ai) |

## 🛠️ Tech Stack

- HTML5, CSS3, JavaScript (jQuery)
- Bootstrap grid system
- Owl Carousel, Magnific Popup, Perfect Scrollbar, Masonry/Shuffle (from the base template)
- Font Awesome (via CDN) for icons
- Inline SVG for custom, dependency-free project graphics

## 📁 Project Structure

```
├── index.html          # Main site (all sections)
├── css/                 # Stylesheets (reset, bootstrap grid, animations, main theme)
├── js/                  # Scripts (jquery, carousel, scroll, popup, form validation)
├── img/                 # Images (profile photo, background, etc.)
├── files/                # Downloadable CV (PDF)
└── README.md            # This file
```

## 🚀 Getting Started

1. Download/clone this folder.
2. Make sure the `css/`, `js/`, and `img/` folders sit alongside `index.html` (same structure as above).
3. Open `index.html` directly in a browser, or serve it locally:
   ```bash
   npx serve .
   ```
4. To update the downloadable CV, replace the PDF at `files/My Resume (Update) (1).pdf`.

## ✏️ Customizing

- Contact info — update the email/phone/address inside the `About Me` and `Contact` sections in `index.html`.
- Portfolio — each project card lives inside `<figure class="item standard">`; update the SVG, title, category, and GitHub link as needed.
- Skills — skill bars are in the `Resume` section (`skill-1` to `skill-9`); update the label and `skill-value` percentage together.
- Social links — update the GitHub/LinkedIn/Twitter `href` values in the header's `.social-links`.

## 👤 Contact

- Email: emaanmubashar@gmail.com
- Phone: +92 321 7261164
- Location: Lahore, Pakistan
- GitHub: [github.com/Emaan-GH](https://github.com/Emaan-GH)

---
*Built and customized with the help of Claude.*