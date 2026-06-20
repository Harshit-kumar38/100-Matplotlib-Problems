# 📊 Matplotlib 100-Question Mastery Challenge

Welcome to the ultimate Matplotlib comprehensive practice repository! This project features a meticulously structured Jupyter Notebook containing exactly **100 python visualization challenges** designed to take you from a complete beginner to a visualization expert. 

By resolving these 100 questions, you will master everything from classic statistical charts to advanced, publication-ready multi-dimensional 3D surfaces and customized interactive aesthetics.

---

##  Datasets Used
The challenges are tightly integrated with real-world open-source datasets included in this repository:
1. **`netflix_titles.csv`**: Contains information on over 8,800 movies and TV shows available on Netflix, including release years, cast, duration, ratings, and global genres. Ideal for exploring categorical distributions, timeline trends, text dimensions, and percentage ratios.
2. **`IPL_Status_2024.csv`**: Features structural performance data of cricket players during the IPL 2024 season. Metrics include positions, runs scored, balls faced, strike rates, matches played, boundaries (4s/6s), and averages. Ideal for numeric correlations, statistical spreads, vector fields, and 3D coordinate graphs.

---

##  Visualizations & Concepts Covered

This practice track completely isolates and deep-dives into 11 indispensable plots and presentation mechanics:

* **2D Line Plots:** Single/multi-axis tracking, rolling averages, continuous time trends, cumulative aggregation, fill regions (`fill_between`), and line path filters.
* **Scatter Plots:** Density distributions, alpha-blended overlaps, multi-variable bubble adjustments, and marginal side-histograms.
* **Histograms:** Relative density estimations, layered comparisons, cumulative growths, step formats, and variable color frequencies.
* **Bar Charts:** Multi-category horizontal/vertical layouts, stacked percentages, bidirectional comparison grids, and error bars.
* **Pie & Donut Charts:** Ratio configurations, customized slices explode mechanics, nested rings, and custom polar vector alignments.
* **Coloured Scatter Charts:** Multi-variable value mapping, sequential vs. divergent color scaling (`TwoSlopeNorm`), colorbars, and logarithmic value distribution grids.
* **Annotations:** Pinpoint arrows (`arrowprops`), data/axis fraction coordinate scaling, floating bounding text boxes (`bbox`), and transparent canvas watermarking.
* **3D Line Plots:** Progression graphs across multiple metrics ($X, Y, Z$), color gradient trajectories, and structural tracking.
* **3D Scatter Plots:** 4-to-5 dimensional projections ($X, Y, Z$ + Size + Color Mapping), camera viewpoint adjustments (`view_init`), and custom grid pane aesthetics.
* **Surface Plots:** 3D grid structures using `np.meshgrid`, bivariate density models, regression trends, and analytical shadowing using `LightSource`.
* **Contour Plots:** 2D isoline thresholds, filled matrix boundaries (`contourf`), inline label optimization (`clabel`), and custom non-linear color transitions.

---

##  Progression Structure

The notebook breaks down your journey into three distinct skill levels to ensure an optimal learning curve:

### 🟢 1. Easy Mode (Questions 1 – 35)
* **Focus:** Core syntax, basic function arguments, labeling, default color variations, and setting up primary 2D & 3D frameworks.
* **Example Challenge:** Extracting numbers from Netflix's movie duration text field and building a standard clean distribution histogram.

### 🟡 2. Medium Mode (Questions 36 – 67)
* **Focus:** Multi-plot layouts, figure composition, complex text styling, dual Y-axes setups, subplots tracking, and custom colormapping.
* **Example Challenge:** Plotting a grouped bar chart showcasing side-by-side comparisons of Movies vs. TV Shows for the top 5 global content-producing countries.

### 🔴 3. Hard Mode (Questions 68 – 100)
* **Focus:** Advanced analytics layouts via `GridSpec`/`subplot2grid`, custom bivariate kernel density estimation mapping, complex string coordinate transformations, vector math surfaces, and production-level exports.
* **Example Challenge:** Fitting a 3D regression surface model modeling player runs based on matches and innings, overlaying original scatter nodes, and exporting a vector-perfect publication-ready PDF.

---

##  Quick Start Installation

Follow these quick steps to get your environment up and running:

1. **Clone or download this workspace folder** ensuring that `netflix_titles.csv`, `IPL_Status_2024.csv`, and `Matplotlib_100_Questions.ipynb` reside together inside the same root directory.
2. **Install or update the dependencies** via terminal using `pip`:
   ```bash
   pip install pandas numpy matplotlib jupyter