QR Code | Minimalist UI Component 📱
A high-fidelity, responsive QR code component featuring System-Aware Dark Mode integration. This project demonstrates a "clean-code" approach to UI elements, utilising TypeScript for theme logic and SCSS for modular styling.

## 📸 Preview

![Minimalist QR code component featuring a centered blue image and clean typography.](./screenshot/screenshot.png)

## 🚀 Technical Highlights

- **Theming Engine:** Custom TypeScript implementation to detect and toggle system/user theme preferences.
- **Markup Architecture:** Pure HTML5 using semantic elements for optimal document structure.
- **Styling Architecture:** Modular SCSS following the BEM (Block Element Modifier) methodology.
- **Modern CSS:** Utilises CSS Custom Properties (Variables) and the light-dark() strategy for seamless theme transitions.
- **Responsive Design:** Mobile-first workflow using relative units (rem) to maintain visual balance.

## 🏗️ Architectural Overview

### 1. TypeScript Theme Management

To go beyond static HTML/CSS, I implemented a logical layer to handle user preferences:
- **Preference Detection:** Uses TypeScript to interface with the window.matchMedia('(prefers-color-scheme: dark)') API, ensuring the UI respects the user's OS settings on load.
- **State Persistence:** (Optional/If applicable) The engine synchronises the theme state across the DOM, applying a data-attribute or class to the root element for consistent styling.
- **Type Safety:** Leverages TypeScript's strict typing to ensure theme tokens are managed without runtime errors.

### 2. Scalable Style System (BEM + SCSS)

The visual architecture is built for maintainability:
- **Thematic Variables:** Defined a robust set of CSS Custom Properties that swap dynamically based on the theme state, eliminating the need for redundant CSS blocks.
- **BEM Methodology:** Ensures that classes remain unique and protected from global style leakage.
- **Performance:** High-performance theme switching with zero layout shift (CLS).

### 3. Structural Precision

- **Flexbox Alignment:** Utilised a dual-axis centring strategy to ensure the card remains perfectly anchored.
- **Typography System:** Implemented a hierarchical font system with specific attention to letter-spacing and contrast ratios (WCAG compliant) in both Light and Dark modes.

## 🛠️ Built With

![SASS](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=SASS&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white)

## 🔗 Live Implementation

- **Live Site:** https://qr-code-component.seanbuckle.com

- **Source Code:** https://github.com/seanbuckle/qr-code-component

## 🏁 Installation & Development

To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/seanbuckle/qr-code-component.git
2. **Navigate to the directory:**
   ```bash
   cd qr-code-component
3. **Open the project:** Simply open `index.html` in your preferred browser.

## 👨‍💻 Author

**Sean Buckle**

[Frontend Mentor Profile](https://www.frontendmentor.io/profile/seanbuckle)

[LinkedIn](https://www.linkedin.com/in/seanbuckle)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/seanbuckle/qr-code-component/blob/main/LICENSE) file for details.

---

***Note: This project was built as a solution to a Frontend Mentor challenge.***
