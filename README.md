# What is this repository

This repository contains the code generating the numbers, graphs and figures displayed in the article :
WHOIS Right? An Analysis of WHOIS and RDAP Consistency

This article is published at the 2024 Passive and Active Measurement (PAM) conference.
The DOI and link to the article will be added here once the proceedings are published.

# The datasets
This repository only contains the Jupyter Notebooks analyzing the data.

The datasets can be downloaded at the following archive:
https://doi.org/10.57745/RJX9XH

# The analysis
To run the analysis:

1. Download the datasets at the link described previously
2. Download the Jupyter Notebooks from this repository
3. Start with the `data_processing.ipynb` notebook. It will parse the datasets, build and clean SQLite databases with all the data, and compute the different missmatches.
4. Go through the `graphs_and_numbers.ipynb` notebook. This notebook extracts data, graphs and plots from the databases built at the previous step, and generate the graphs present in the article

# Contact
If you have any question or have trouble running the analysis, contact the article authors or open an issue in this repository
