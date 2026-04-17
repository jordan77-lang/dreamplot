# DreamPlot

DreamPlot is a real-time, lightweight, browser-based curve fitting tool designed for student data analysis. Plot data points, visualize mathematical models, and extract best-fit equations directly in the browser — no installation required.

Live Demo: [https://jordan77-lang.github.io/dreamplot/](https://jordan77-lang.github.io/dreamplot/)

## Features

### Data Entry
* **Manual Entry:** Enter X and Y values individually and click Add.
* **Bulk Import:** Paste two columns directly from Excel or Google Sheets.
* **Canvas Mode:** Click directly on the graph to place points interactively.
* **Drag Points:** Click and drag any existing point to reposition it in real-time.

### Curve Fitting
* **Six Models:** Linear, Quadratic, Cubic, Exponential, Logarithmic, and Power Law.
* **Real-time Fitting:** Equation and statistics update instantly as points are added or moved.
* **Best Fit Equation:** Displayed with a one-click copy button.
* **R² Statistic:** Coefficient of Determination to judge the quality of the fit.
* **Average % Error:** Shown alongside R² and point count.

### Prediction
* **Enter X → get Y:** Calculates the predicted Y value from any X input.
* **Enter Y → get X:** Solves the model in reverse to find the corresponding X value.

### Graph
* **Interactive Canvas:** Scroll to zoom, shift+drag to pan, drag points to move.
* **Guided Help:** Use the Help button in the header for an overview, then click the small ? buttons beside section titles for more specific instructions.
* **Smart Grid:** Nice-numbers algorithm spaces grid lines at clean 1, 2, or 5 multiples.
* **Axis Labels:** Automatically switch to scientific notation for very large or small values.
* **Graph Settings:** Customise axis labels and manually set axis bounds.

### Export & Persistence
* **Generate Report:** Opens a polished print-friendly report with the graph, fit summary, and full data table.
* **PNG Export:** Download the current graph as an image.
* **CSV Export:** Download raw data points as a spreadsheet-ready file.
* **Auto-Save:** Automatically saves points, labels, and model to browser LocalStorage.

## Usage
Open `index.html` in any modern web browser. No build process, dependencies, or local server required.
