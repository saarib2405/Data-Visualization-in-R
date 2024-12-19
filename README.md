# Twitter Sentiment Analysis with Llama-3-8B

This project enables sentiment analysis and tone classification of tweets using the fine-tuned Meta Llama-3-8B-Instruct model. It uses Hugging Face's transformers library and Gradio for creating an interactive interface.

## Table of Contents
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Code Description](#code-description)
- [How to Run](#how-to-run)
- [Acknowledgments](#acknowledgments)

---

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/twitter-sentiment-analysis.git
    cd twitter-sentiment-analysis
    ```

2. Set up a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## Dependencies

Here are the dependencies and their versions required for this project:

- **R** >= 4.0.0
- **ggplot2** >= 3.3.5
- **corrplot** >= 0.92

The required R packages can be installed using:
```R
install.packages("ggplot2")
install.packages("corrplot")
```

---

## Usage

This project uses R for data visualization and statistical analysis. It includes examples of creating histograms, scatter plots, box plots, bar plots, pairwise scatter plots, and correlation matrices.

### Steps:
1. Install R and RStudio on your system if not already installed.
2. Install the required libraries using the commands provided in the Dependencies section.
3. Copy the script into an R script file or RMarkdown file.
4. Execute the script in RStudio or any R-compatible IDE to generate visualizations and analysis.

---

## Code Description

The script contains:

1. **Data Generation:**
    - Synthetic data for histograms using `rnorm`.
    - A data frame for correlation matrix computation.

2. **Visualizations:**
    - Histograms: Overlapping histograms with legends.
    - Scatter plots: Relationships between variables like horsepower and MPG.
    - Box plots: Distribution of MPG by cylinder count or transmission type.
    - Bar plots: Frequency distribution of categorical variables.
    - Pie chart: Visual representation of categorical proportions.
    - Correlation matrix: A heatmap using the `corrplot` library.

3. **Libraries Used:**
    - `ggplot2` for advanced plots.
    - `corrplot` for correlation visualization.

---

## How to Run

1. Open the R script in RStudio.
2. Run the script section by section to generate the visualizations.
3. Explore the outputs, including histograms, bar plots, scatter plots, box plots, and correlation matrix.
