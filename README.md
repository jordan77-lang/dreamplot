# DreamPlot

DreamPlot is a real-time, lightweight, browser-based curve fitting tool designed for easy data analysis. It allows users to quickly plot data points, visualize different mathematical models, and extract best-fit equations directly in the browser—no installation required.

Live Demo: [https://jordan77-lang.github.io/dreamplot/](https://jordan77-lang.github.io/dreamplot/)

## Versions

This repository contains two versions of the tool:

### Version 1 (`index.html`)
The original, streamlined version of DreamPlot.
* **Core Fitting Models:** Linear, Quadratic, Cubic, Exponential, Logarithmic, and Power Law.
* **Interactive Canvas:** Click to add points, shift+drag to pan, scroll to zoom.
* **Real-time Stats:** Instantly calculates the equation of the line and Mean Absolute Percentage Error (MAPE).
* **Bulk Import:** Paste coordinates from spreadsheets or text files.
* **Point Tooltips:** Click any point to view its coordinates, predicted value, and residual error.
* **Predictability:** Enter an X or Y value to instantly calculate the corresponding coordinate on the best-fit line.

### Version 2 (`v2.html`)
An advanced version packed with additional professional-grade features and improved UI/UX, while maintaining the lightweight nature of V1.

**New Features in V2:**
* **R² Statistic:** The stats panel now includes the Coefficient of Determination ($R^2$) to easily judge the quality of a fit.
* **Auto-Recommend Best Fit:** The tool automatically calculates the $R^2$ for every valid model in the background and places a green ★ (star) badge on the button of the model that provides the best fit for your data.
* **Residuals Mini-Plot:** A secondary plot automatically appears beneath the main canvas showing the residuals (error) for each point, helping to visually identify outliers or non-random error patterns.
* **Draggable Points:** You can now click and drag existing points around the canvas to see the curve conform to the new data in real-time.
* **Data Export:** Added **⬇ PNG** and **⬇ CSV** buttons to the header to quickly download your graph image or your raw coordinate data.
* **Local Auto-Save:** Automatically saves your points, labels, and chosen model to your browser's LocalStorage. If you accidentally refresh or close the tab, your data will be exactly as you left it.
* **Smart Grid & Axes:** The grid lines now use a "nice-numbers" algorithm (spacing by 1, 2, or 5 multiples), and axis labels automatically switch to scientific notation for very large or small numbers.
* **Copy Equation Clipboard:** A quick-copy clipboard button sits next to the best-fit equation.
* **Improved Bulk Import:** Better handling for "two-column" paste formats coming from Google Sheets or Excel.

## Usage
Simply open `index.html` or `v2.html` in any modern web browser to start using the tool. No build process, dependencies, or local server is required.
