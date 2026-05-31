Project Completion: Finalizing and summarizing the "Decision Debt Calculator" project.


✦ I have completed the Decision Debt Calculator. It is a polished, production-ready single-file web application designed with a premium SaaS aesthetic.

  Key Features Delivered:
   - Weighted Decision Matrix: A robust engine that calculates scores based on your custom criteria and importance levels.
   - Scenario Engine: Five one-click presets (Balanced, Short Term, Growth, Safety, Freedom) that instantly reconfigure weights to reflect different life priorities.
   - Real-Time Visualizations:
       - Horizontal Bar Chart: Compares overall weighted percentages.
       - Radar Chart: Maps the unique "profile" of each option across all criteria.
   - Dynamic Insights: An automated recommendation system that identifies the winner, explains why it won, and highlights potential trade-offs.
   - Premium UX:
       - Full Dark Mode and Light Mode support.
       - Responsive design for mobile and desktop.
       - Print-optimized reporting for PDF exports.
   - Interactive Matrix: Inline editing of option names, criteria names, weights, and scores with instant UI updates.

  How to Use:
   1. Open the Decision Debt Calculator.html file in any modern web browser.
   2. Click "Sample Data" to see an immediate comparison between an MBA, a Job Switch, and a Startup.
   3. Toggle the Scenario buttons to see how the rankings change based on different priorities.
   4. Use "Print Report" to generate a clean, professional summary of your decision.

  The app is completely self-contained with no external dependencies other than Chart.js and Inter font via CDN, making it perfect for both local use and portfolio hosting.
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
# Decision Debt Calculator

A premium, professional-grade web application designed to help students and professionals navigate complex career and life choices using a data-driven weighted decision matrix.

## 🚀 Overview

Decision paralysis often stems from the inability to compare subjective trade-offs clearly. The **Decision Debt Calculator** converts intuitive feelings into quantifiable data, allowing you to compare options like an MBA, a startup, or a job switch with logical rigor.

## ✨ Key Features

- **Weighted Decision Matrix**: Assign importance levels (0-100%) to various criteria to reflect your personal priorities.
- **Scenario Presets**: Instantly rebalance your priorities with one-click scenarios:
  - **Balanced**: Equal focus on growth, safety, and reward.
  - **Short Term**: Prioritizes immediate salary and fast payoff.
  - **Growth**: Focuses on learning and future upside.
  - **Safety**: Minimizes risk and emphasizes stability.
  - **Freedom**: Prioritizes flexibility and personal passion.
- **Real-Time Visualizations**:
  - **Performance Bar Chart**: Compares the final weighted scores of all options.
  - **Radar/Spider Chart**: Visualizes the unique "shape" of each option across all criteria.
- **Dynamic Recommendations**: Plain-language explanations of the top choice, including its primary strength and a critical trade-off.
- **Premium Design System**: Full support for **Light and Dark modes**, responsive layouts for mobile, and a specialized **Print-to-PDF** report view.

## 📊 Logic & Methodology

The app uses a standard **Weighted Decision Matrix (WDM)** model:
1. **Normalization**: Each criterion is assigned a weight.
2. **Scoring**: Options are scored on a scale of 1-10 for each criterion.
3. **Calculation**: `Final Score = Σ (Criterion Weight × Option Score)`.
4. **Ranking**: Options are ranked by their final weighted percentage relative to the maximum possible score.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure.
- **CSS3**: Custom design system with CSS variables for theme switching.
- **Vanilla JavaScript**: State management and calculation logic (no frameworks).
- **Chart.js**: High-performance data visualization via CDN.
- **Inter Font**: Professional typography via Google Fonts.

## 📂 Data Sources & Defaults

The application is entirely client-side and does not require a backend or database.
- **Default Criteria**: Salary, Learning, Risk, Time to Payoff, Flexibility, Passion.
- **Sample Dataset**: Includes a pre-configured comparison between an **Executive MBA**, a **Job Switch**, and a **Startup**.

## 🌐 Deployment & Hosting

This app is a single-file solution, making it extremely easy to host for free:

### **Suggested Host URL Format**
`https://decision-debt-calculator.netlify.app` or `https://[your-username].github.io/decision-debt-calculator`

### **How to Host (In 30 Seconds):**
1. **Netlify Drop**: Drag and drop the `Decision Debt Calculator.html` file into [Netlify Drop](https://app.netlify.com/drop).
2. **GitHub Pages**: Upload the file to a GitHub repository, rename it to `index.html`, and enable "Pages" in the repository settings.
3. **Vercel**: Use the Vercel CLI or connect your GitHub repo for instant deployment.

---

*Built with precision to help you trade debt for decisions.*
