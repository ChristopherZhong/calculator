# OmniCalc

OmniCalc is a full-featured, modern minimalist calculator built with vanilla HTML, CSS, and TypeScript. It leverages the power of **Web Components** for a modular and performant experience, and is designed to be easily deployed to GitHub Pages.

## ✨ Features

- **Basic Arithmetic:** Addition, subtraction, multiplication, and division.
- **Scientific Mode:** Access advanced functions like square root, power (xʸ), trigonometric functions (sin, cos, tan), logarithms, and constants (π, e).
- **History Log:** Keep track of your previous calculations and recall them with a click.
- **Dark/Light Mode:** Seamlessly toggle between light and dark themes to suit your preference.
- **Modern Minimalist UI:** Clean lines, subtle shadows, and a focus on usability.
- **Responsive Design:** Fully functional on both desktop and mobile devices.
- **Keyboard Support:** Speed up your calculations using your keyboard:
  - Numbers: `0-9`
  - Operators: `+`, `-`, `*`, `/`
  - Result: `Enter` or `=`
  - Clear: `Escape`
  - Backspace: `Backspace`
  - Decimal: `.`

## 🛠️ Tech Stack

- **Language:** TypeScript
- **Framework:** None (Vanilla JS with Web Components)
- **Build Tool:** Vite
- **Styling:** CSS3 (using CSS Variables)
- **Font:** [Inter](https://fonts.google.com/specimen/Inter)

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/omnicalc.git
   cd omnicalc
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the development server:
```bash
npm run dev
```

### Build

To create a production-ready build in the `dist` folder:
```bash
npm run build
```

### Deployment

This project is configured for easy deployment to GitHub Pages. After building the project, you can deploy the `dist` folder.

## 🎨 Design Philosophy

OmniCalc follows a **Modern Minimalist** design philosophy. By removing unnecessary clutter and focusing on whitespace and typography, it provides a calm and efficient user experience. The use of CSS variables ensures that theme switching is smooth and consistent across all components.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
