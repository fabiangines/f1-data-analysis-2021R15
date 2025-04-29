# Formula 1 Data Analysis

![Logo](man/figures/logo.png) <!-- Optional: Add your project logo -->

## Description

This project analyzes Formula 1 lap time data using the `f1dataR` R package. The analysis includes visualizations and insights derived from the data obtained from the Jolpica API and the FastF1 Python library.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Functions](#functions)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use this project, you need to have R and the necessary packages installed. You can install the `f1dataR` package from CRAN or GitHub:

```r
# Install from CRAN
install.packages("f1dataR")

# Or install the development version from GitHub
if (!require("remotes")) install.packages("remotes")
remotes::install_github("SCasanova/f1dataR")

## Usage

1. **Clone the repository to your local machine**:
   Open your terminal or command prompt and run the following command:
   ```bash
   git clone https://github.com/YourUsername/f1-data-analysis.git
