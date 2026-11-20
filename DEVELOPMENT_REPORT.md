# Portfolio Development Report — Yusof Rafsin

> **Assignment:** Desktop & Web Programming-PS (Fall 2026)  
> **Student:** Yusof Rafsin  
> **Program:** Software Engineering  
> **Institution:** Daffodil International University  
> **Report status:** Draft — review and personalize before submission


## 1. Introduction and Objective
The objective of this project was to create a responsive personal portfolio website that introduces my academic background, technical skills, learning interests, and project concepts. I used the portfolio as a small frontend project to practice semantic HTML, styling, responsive layouts, and JavaScript interaction while creating a professional online profile.


## 2. Planning and Design
I chose a dark, editorial developer aesthetic rather than a conventional portfolio template. The visual direction uses a charcoal background, restrained lime accent, high-contrast typography, compact labels, bordered cards, and generous spacing. The design is intended to feel technical and modern while remaining readable.


## 3. Website Structure
The site is divided into these sections:
- **Hero:** name, role, short introduction, profile photograph, and navigation to work/contact.
- **About:** introduction and quick facts.
- **Skills:** programming, web development, CS/data foundations, tools, and currently exploring.
- **Education:** a timeline for SSC, HSC, and current university study.
- **Projects:** four academic/personal project concepts with technology tags.
- **Direction:** learning priorities and career objective.
- **Contact:** email links.


## 4. Technologies and Tools
- **HTML5:** semantic sections, headings, navigation, links, and accessible image text.
- **CSS3:** responsive grids, flex layouts, custom properties, hover states, media queries, and visual styling.
- **JavaScript:** mobile navigation toggle, current year, and scroll reveal effects with Intersection Observer.
- **Visual asset:** my supplied profile photo.
- **Fonts:** Manrope and DM Mono via Google Fonts.

The site is static and does not require a framework, dependencies, or a build process.


## 5. Implementation Strategy
I separated the website into three main files: `index.html` for structure, `style.css` for layout and design, and `script.js` for interaction. The CSS uses reusable variables for colors and spacing. Layout changes are handled with media queries so the content adjusts from desktop to mobile. JavaScript controls the mobile navigation and progressive reveal of sections. The portfolio remains straightforward to host on static platforms such as GitHub Pages, Netlify, or Vercel.


## 6. AI Tool Use
AI assistance was used to help plan the visual direction, organize the content into sections, draft frontend structure and styling, and review implementation details. Example prompts used during development:

1. “Design a distinctive responsive portfolio for a Software Engineering student using only HTML, CSS, and vanilla JavaScript. Avoid a generic template and use a dark editorial layout with one accent color.”
2. “Create an accessible mobile navigation menu and lightweight reveal animations using vanilla JavaScript. Respect reduced-motion preferences.”
3. “Review this portfolio content for clarity and ensure project descriptions do not overstate work that is only a concept or learning exercise.”

AI-generated suggestions were treated as starting points. I reviewed the section structure, visual hierarchy, mobile behavior, and wording, then adjusted the layout and content to match the information available about my academic profile. Project entries are explicitly described as concepts/learning projects where completion or live links were not provided.


## 7. Challenges and Solutions
- **Responsive layout:** The desktop two-column sections could become crowded on small screens. I used CSS breakpoints to stack the layout and simplify navigation on mobile.
- **Visual consistency:** Color, borders, spacing, and typography were centralized through CSS variables and reused across cards and sections.
- **Interactivity without frameworks:** JavaScript was kept small and focused on navigation, scroll reveal, and the dynamic footer year.
- **Content accuracy:** Unknown social profile URLs and project repositories were not invented. The report and website should be updated with verified links before final submission.


## 8. Testing and Deployment
Test the portfolio at desktop and mobile widths, check that the navigation anchors work, verify the profile image loads, and test the email links. Deployment can be done through GitHub Pages, Netlify, or Vercel. For GitHub Pages, publish the repository root from the `main` branch and then copy the generated live URL into the assignment Google Sheet.


## 9. Learning Outcome and Conclusion
This project provides practice in planning a frontend page, organizing content with semantic HTML, styling a responsive interface with CSS, and adding small interactions with JavaScript. It also demonstrates how AI tools can support ideation and coding while requiring human review for accuracy, accessibility, and personal details. The portfolio can continue to grow as I complete additional projects and learn new technologies.


## 10. Final Submission Checklist
- [ ] Replace or add verified GitHub and LinkedIn profile URLs.
- [ ] Add links to real project repositories/demos when available.
- [ ] Review the profile and project text for accuracy.
- [ ] Test on phone and desktop.
- [ ] Deploy and record the live URL.
- [ ] Submit live URL in the provided class Google Sheet.
- [ ] Add screenshots of the final site to this report if your instructor expects evidence.
