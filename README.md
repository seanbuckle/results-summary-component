# Results Summary | Data-Driven UI Component 📊
A high-performance, accessible results summary interface that dynamically renders performance metrics. This project showcases **TypeScript-integrated JSON mapping**, sophisticated **CSS Gradient layering**, and a robust **BEM-structured SCSS** architecture.

## 📸 Preview

![A professional UI preview of the Results Summary component featuring a split-card design with a dynamic score circle and categorized metric breakdowns.](./images/screenshot.png)

## 🚀 Technical Highlights

- **Type-Safe Data Mapping:** Utilises **TypeScript** to fetch and map local `data.json` content, ensuring type integrity across category labels, scores, and iconography.
- **Dynamic DOM Injection:** Engineered a modular rendering pipeline that generates list items dynamically based on the data source, promoting dry code and scalability.
- **Complex Gradient Composition:** Implemented multi-layered **CSS Gradients** and transparency effects to achieve the high-fidelity depth seen in the original design.
- **Responsive Adaptive Layout:** Leverages a **Mobile-First** strategy with a seamless transition from a vertical stack to a dual-pane horizontal layout using **CSS Grid**.
- **Performance Optimised:** Achieves near-perfect Lighthouse scores through optimised SVG assets and minimal execution overhead.

## 🏗️ Architectural Overview

### 1. Data Orchestration & TypeScript

The component is designed to be content-agnostic:
- **Interface Contracts:** Defined a strict `ResultItem` interface to validate incoming data attributes (category, score, icon, theme-color).
- **Asynchronous Flow:** Uses the `Fetch API` to simulate a real-world dashboard environment where data is retrieved from a backend or local JSON file.
- **Functional Mapping:** Implemented `.map()` logic to iterate through data, injecting categorised scores into the DOM with specific color tokens.

### 2. Design System (SCSS + BEM)

- **Modular Architecture:** Built using **SCSS partials** and the **BEM (Block Element Modifier)** methodology for strict component encapsulation.
- **Design Tokens:** Extensive use of **CSS Custom Properties** for the color palette, allowing for easy theme switching (e.g., dynamic opacity for category backgrounds).
- **Fluid Typography:** Utilises the 'Hanken Grotesk' typeface with optimised line heights to maintain legibility across various viewport densities.

### 3. Accessibility & UX

- **Semantic Structure:** Uses `<section>` and `<ul>` elements to ensure the summary is navigable by screen readers and search engine crawlers.
- **Interactive States:** Custom focus and hover transitions on the "Continue" trigger, utilising `box-shadow` and `transform` properties for a tactile feel.
- **Color Contrast:** Verified color pairings against WCAG standards to ensure data readability.

## 🛠️ Built With

![TYPESCRIPT](https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge&logo=TYPESCRIPT&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=SASS&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white)

## 🔗 Live Implementation

- **Live Site:** https://github.com/seanbuckle/results-summary-component

- **Source Code:** https://results-summary-component.seanbuckle.com

## 🏁 Installation & Development

To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/seanbuckle/results-summary-component.git
2. **Navigate to the directory:**
   ```bash
   cd results-summary-component
3. **Open the project:** Simply open `index.html` in your preferred browser.

## 👨‍💻 Author

**Sean Buckle**

[Frontend Mentor Profile](https://www.frontendmentor.io/profile/seanbuckle)

[LinkedIn](https://www.linkedin.com/in/seanbuckle)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/seanbuckle/results-summary-component/blob/main/LICENSE) file for details.

---

***Note: This project was built as a solution to a Frontend Mentor challenge.***
