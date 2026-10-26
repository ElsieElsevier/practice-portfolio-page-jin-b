# Jin (Ken) Bai — Professional Portfolio

A personal portfolio website built with semantic HTML and CSS. It showcases my background as a Cloud Engineer, Cybersecurity professional, Data Engineer, and Software Developer, along with my skills, certifications, research, and projects.

## Sections

| Section | Contents |
| --- | --- |
| **Header** | Name, titles, and links to GitHub and LinkedIn |
| **About Me** | Professional summary and downloadable resumes (Cloud Engineer, Security Operations, Data Engineer) |
| **Technical Skills** | Table of skills with proficiency levels |
| **Certifications** | CompTIA Security+ and AWS Certified Cloud Practitioner with verification links |
| **Research & Publication** | *Neural Thurstone Model* (Cognitive Science Society, 2025) with publication links |
| **Projects** | Arrange.ly, an ML-powered wedding seating optimizer (eHack 2025, Second Place) with link to project repository |
| **Contact** | Contact form with name, email, and message fields |

## Built With

- **HTML5**: semantic elements (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3**: Flexbox, the box model, and responsive sizing
- **Google Fonts**: [Ubuntu Mono](https://fonts.google.com/specimen/Ubuntu+Mono)

## Key Concepts Demonstrated

### HTML
- **Semantic structure** for accessibility and readability, following a clear heading hierarchy (`h1` → `h2` → `h3`)
- **Accessible forms**: each `label` is linked to its input through `for`/`id` and has built-in validation using `required` and `type="email"`
- **Secure external links**: `target="_blank"` paired with `rel="noopener"` to prevent reverse tabnabbing
- **Image accessibility** with descriptive `alt` text
- **Responsive viewport** setup with the `viewport` meta tag

#### What is Reverse Tabnabbing?
When you click on a link that opens it in a new tab using `target="_blank"`, the new page can get a reference back to your the `window.opener` property.
A malicious page can use that to quietly redirect your original tab to a fake look-alike phishing log in page while you're browsing the new tab.
When you switch back, you think you're on the original page but it's actually a fake.
Using `rel="noopener"` severs that link so the `window.opener` property is null and the new page can't touch your tab.

### CSS
- **Inheritance**: the font is set once on `body` and inherited by the rest of the page
- **Box model**: `box-sizing: border-box` keeps padding inside an element's set width
- **Flexbox**: link buttons are centered and wrap with `justify-content`, `flex-wrap`, and `gap`
- **Responsive layout without media queries**: percentage widths with `max-width` and using plus fluid images (`max-width: 100%; height: auto`)
- **Centering techniques**: `margin: auto`, `text-align: center`, and Flexbox
- **Interactive states**: `:hover` styles on link buttons
- **Grouped selectors** to avoid repeating rules

## Project Structure

```
.
├── index.html
├── style.css
├── images/
│   └── IMG_8001.jpg
└── resumes/
    ├── CloudEngineerResume.pdf
    ├── SecOpsEngineerResume.pdf
    └── DataEngineerResume.pdf
```

## Contact

- **GitHub:** [ElsieElsevier](https://github.com/ElsieElsevier)
- **LinkedIn:** [jin-bai](https://www.linkedin.com/in/jin-bai/)

---

© 2026 Jin Bai. All rights reserved.
