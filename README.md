# QR Code | Minimalist UI Component 📱
A high-fidelity, responsive QR code component built with a focus on layout precision and modular styling. This project demonstrates a "clean-code" approach to simple UI elements, utilising SCSS and Semantic HTML5.

## 📸 Preview

![Minimalist QR code component featuring a centered blue image and clean typography.](./screenshot/screenshot.png)

## 🚀 Technical Highlights

- **Markup Architecture:** Pure HTML5 using semantic elements for optimal document structure.
- **Styling Architecture:** Modular SCSS following the BEM (Block Element Modifier) methodology to ensure encapsulated, reusable styles.
- **Layout Engine:** CSS Flexbox and Grid used in tandem to achieve perfect centring and internal padding.
- **Responsive Design:** Mobile-first workflow using relative units (rem, px) to maintain visual balance across all screen sizes.
- **Asset Optimisation:** High-resolution rendering and optimised font loading for a sharp, professional finish.

## 🏗️ Architectural Overview

### 1. Structural Precision

While the design is minimalist, achieving a "pixel-perfect" match requires a disciplined approach to the box model:
- **Card Encapsulation:** The component is built as a self-contained block, allowing it to be easily ported into larger dashboards or landing pages.
- **Flexbox Alignment:** Utilised a dual-axis centring strategy to ensure the card remains perfectly anchored in the viewport regardless of device orientation.
- **Typography System:** Implemented a hierarchical font system with specific attention to letter-spacing and line-height for maximum legibility.

### 2. Scalable Style System (BEM + SCSS)

Following the "Product Suite" standard, the styles are organised for long-term maintainability:
- **BEM Methodology:** Ensures that classes like `.qr-card__image` and `.qr-card__title` remain unique and protected from global style leakage.
- **Variables & Mixins:** Leveraged SCSS variables for the color palette and spacing scale, allowing for instant global theme updates.
- **Performance:** Zero-dependency CSS ensures lightning-fast paint times and a perfect Core Web Vitals score.

### 3. Accessible Implementation

- **Alt Text Optimisation:** Descriptive metadata for the QR image ensures that screen reader users understand the context of the component.
- **Logical Flow:** The heading structure is optimised for SEO and assistive technology navigation.

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
