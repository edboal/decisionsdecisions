# Decisions²

Decisions² is an interactive decision tree builder that allows users to create, customize, and share branching pathways, flowcharts, and guided step-by-step processes.

## 🌟 Key Features

* **Visual Node Editor:** Create "Question" nodes (with multiple branching options) and "Result" nodes (endpoints). Easily link options to next steps to build complex logic trees.
* **Dual Viewing Modes:**
  * **Step View:** A focused, interactive step-by-step mode where users are presented with one question at a time.
  * **Tree View:** A comprehensive, auto-layout flowchart view (powered by React Flow and Dagre) that visualizes the entire decision path.
* **Live Preview:** A split-screen interface that lets creators instantly test and interact with their decision tree as they build it.
* **Theming & Customization:** A built-in theme editor allows creators to customize background colors, primary accent colors, text colors, button styles, border radii, and fonts.
* **Export & Sharing:**
  * **URL Sharing:** The entire state of the decision tree is compressed and encoded directly into the URL. This allows for instant sharing without needing a backend database.
  * **Embed Mode:** Generates an iframe snippet so the interactive tree can be embedded directly into other websites or Notion docs.
  * **PDF Export:** Download a high-quality PDF snapshot of either the current step or the entire flowchart.

## 🚀 Getting Started

### Prerequisites
* Node.js (v18 or higher)
* npm or yarn

### Installation
1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## 📁 Project Structure

* `/src` - Contains all the React components, styles, and application logic.
* `/public` - Contains static assets like the `favicon.svg` and any other images. These files are served directly at the root path.
