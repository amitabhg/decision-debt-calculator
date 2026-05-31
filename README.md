# Decision Debt Calculator

A premium, professional-grade web application designed to help students and professionals navigate complex career and life choices using a data-driven weighted decision matrix.

## 🚀 Overview

Decision paralysis often stems from the inability to compare subjective trade-offs clearly. The **Decision Debt Calculator** converts intuitive feelings into quantifiable data, allowing you to compare options like an MBA, a startup, or a job switch with logical rigor.

## ✨ Key Features

- **Weighted Decision Matrix**: Assign importance levels (0-100%) to various criteria to reflect your personal priorities.
- **Scenario Presets**: Instantly rebalance your priorities with one-click scenarios (Balanced, Short Term, Growth, Safety, Freedom).
- **Market Insights & Discovery Feed**: Dynamically generates contextual intelligence cards (Jobs, Education, Startup Trends) based on your chosen options with direct links to live market data.
- **Real-Time Visualizations**: 
  - **Performance Bar Chart**: Compares final weighted scores.
  - **Radar/Spider Chart**: Visualizes the unique multi-dimensional profile of each option.
- **Dynamic Recommendations**: AI-style plain-language explanations of the top choice, highlighting primary strengths and critical trade-offs.
- **Premium Design System**: Full support for **Light and Dark modes**, mobile-responsive layouts, and a specialized **Print-to-PDF** report view.

## 📊 Logic & Methodology

The app uses a standard **Weighted Decision Matrix (WDM)** model:
1. **Normalization**: Each criterion is assigned a weight.
2. **Scoring**: Options are scored on a scale of 1-10 for each criterion.
3. **Calculation**: `Final Score = Σ (Criterion Weight × Option Score)`.
4. **Ranking**: Options are ranked by their final weighted percentage relative to the maximum possible score.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure.
- **CSS3**: Custom design system with CSS variables for theme switching.
- **Vanilla JavaScript**: Reactive state management and calculation logic.
- **Chart.js**: High-performance data visualization via CDN.
- **Inter Font**: Professional typography via Google Fonts.

## 📂 Data Sources & Defaults

- **Default Criteria**: Salary, Learning, Risk, Time to Payoff, Flexibility, Passion.
- **Sample Dataset**: Includes a pre-configured comparison between an **Executive MBA**, a **Job Switch**, and a **Startup**.
- **External Discovery**: Integrates deep-linked searches for LinkedIn (Jobs), Google/QS (Education), and Product Hunt (Startup trends).

## 🌐 Deployment & Hosting

This app is a single-file solution, making it extremely easy to host:

### **Suggested Host URL**
`https://amitabhg.github.io/decision-debt-calculator`

### **How to Deploy:**
1. **GitHub Pages**: 
   - Create a repo named `decision-debt-calculator`.
   - Upload `Decision Debt Calculator.html` and rename it to `index.html`.
   - Enable "Pages" in repository settings.
2. **Netlify Drop**: Drag and drop the file into [Netlify Drop](https://app.netlify.com/drop).

---

*Built with precision to help you trade debt for decisions.*
