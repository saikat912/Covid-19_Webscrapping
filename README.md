# Web Scraping Project: COVID-19 Data Analysis and Visualization

## Table of Contents

-   [Introduction](#introduction)
-   [Features](#features)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Data Sources](#data-sources)
-   [Data Analysis and Visualization](#data-analysis-and-visualization)
-   [Regional Classification](#regional-classification)
-   [Limitations](#limitations)
-   [Contributing](#contributing)
-   [License](#license)
-   [Contact](#contact)

## Introduction

This project focuses on web scraping, analysis, and visualization of COVID-19 data from various online sources. It extracts real-time information, organizes it into structured formats, and performs regional classification based on the United Nations Geoscheme to provide insights into the pandemic's impact.

## Features

-   Scrapes real-time COVID-19 data, including total cases, new cases, total deaths, and recoveries from Worldometer and other sources.
-   Organizes data into tabular formats using pandas DataFrames for easy manipulation and analysis.
-   Classifies data by geographic regions based on the United Nations Geoscheme for regional analysis.
-   Computes statistics such as cases per million population, deaths per million population, etc., to normalize the data.
-   Provides data visualization using Matplotlib and Seaborn for exploratory data analysis, including trends of total cases vs. total recoveries.
-   Exports processed data to CSV files for further analysis or integration with other systems.

## Installation

1.  **Clone the repository:**

    ```
    git clone <repository_url>
    cd web-scraping-project
    ```

2.  **Install dependencies:**
    ```
    pip install -r requirements.txt
    ```

    **requirements.txt:**

    ```
    pandas
    beautifulsoup4
    requests
    matplotlib
    seaborn
    jupyter
    ```

3.  **Run Jupyter Notebook:**

    ```
    jupyter notebook Copy-of-Updated-Web-Scaping-11th-Feb-2024.ipynb
    ```

## Usage

1.  Open the Jupyter Notebook `Copy-of-Updated-Web-Scaping-11th-Feb-2024.ipynb`.
2.  Execute each cell sequentially to scrape, process, and analyze the data.
3.  Modify parameters such as regions or data sources within the notebook to customize the analysis.
4.  The notebook provides outputs such as DataFrames, visualizations, and saved CSV files.


## Data Sources

The project primarily uses data from:

*   [Worldometer](https://www.worldometers.info/coronavirus/)
*   Specific sources referenced as "Latest News" in the notebook (details in the notebook itself)

## Data Analysis and Visualization

The notebook includes data visualization to help understand trends and patterns in the COVID-19 data. One of the key visualizations is a plot showing the relationship between total cases and total recoveries.

![Total Cases vs Total Recovered](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/15804853/cf415142-f4e5-45a8-aae6-b964ec3c722d/Copy-of-Updated-Web-Scaping-11th-Feb-2024.ipynb)

*This graph illustrates the trend between total COVID-19 cases and total recoveries globally.*  *(based on data scraped on February 11th, 2024)*. The X-axis represents "Total Cases", while the Y-axis represents "Total Recovered."

## Regional Classification

Countries are classified according to the United Nations Geoscheme for statistical purposes. This allows for aggregated regional analysis, facilitating comparisons between different regions.

## Limitations

*   Data accuracy depends on the source websites. Web scraping results rely on the structure and availability of the source data.
*   Web scraping can be affected by changes in website structure, requiring adjustments to the scraping logic.
*   The project's results are based on available data and may not reflect all cases, particularly in regions with limited data reporting.

## Contributing

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Commit your changes with descriptive messages.
4.  Push your branch to your forked repository.
5.  Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

*   **Saikat Pal**
*   **saikatpal912@gmail.com**
*   **saikat912**



