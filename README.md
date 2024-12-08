# Scraping Selenium-Pandas Pipeline: Extraction, Transformation, and Analysis of Voting Data for the  Supreme Court Election in Guatemala 2024

## Project Overview

This project automates the extraction, transformation, and analysis of voting data from the official website of the Congress of Guatemala. The focus is the election process for Supreme Court magistrates held in October 2024, where congressmen vote for or against candidates. The project uses a notebook-based approach to guide users through the workflow, making it accessible for both technical and non-technical audiences.

Key outputs include structured CSV files, an adjacency matrix for network analysis, and insights into voting patterns and relationships between deputies and candidates.

---

## Features

- **Automated Web Scraping**: Extracts dynamic content from the Congress website using Selenium.
- **Data Cleaning and Transformation**: Standardizes voting data into a binary format (`1` for "A FAVOR" and `0` for "CONTRA"/null).
- **Adjacency Matrix**: Generates a matrix representing relationships between congressmen and candidates.
- **Network Analysis Ready**: Provides structured data suitable for tools like Gephi to analyze voting patterns visually.
- **Dual-Language Support**: Includes notebooks in both English and Spanish for wider accessibility.

---

## Repository Structure

```
Scraping_supreme_court_election_gt_2024/
├── Scraping_supreme_court_election_gt.ipynb  # Notebook in English
├── Scraping_eleccion_CSJ_gt.ipynb            # Notebook in Spanish
└── files/                                    # Directory for CSV outputs (created when running the notebook)
```

---

## Notebooks

### 1. **Scraping_supreme_court_election_gt.ipynb (English)**
   - A detailed guide to the project in English, including:
     - Installing required libraries.
     - Extracting voting data using Selenium.
     - Transforming data with pandas.
     - Creating and exporting the adjacency matrix for network analysis.

### 2. **Scraping_eleccion_CSJ_gt.ipynb (Spanish)**
   - A comprehensive guide to the project in Spanish, covering the same workflow and explanations as the English notebook.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/cdberganza/Scraping_supreme_court_election_gt_2024.git
   cd Scraping_supreme_court_election_gt_2024
   ```

2. **Run the Notebook**:
   Open the notebook in your preferred language using Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook Scraping_supreme_court_election_gt.ipynb
   ```
   or
   ```bash
   jupyter notebook Scraping_eleccion_CSJ_gt.ipynb
   ```

3. **Install Required Libraries**:
   The notebooks include a code cell for installing all necessary libraries. Run the cell if the libraries are not already installed.

---

## Key Outputs

1. **CSV Files**:
   - Generated for each candidate, detailing votes cast by congressmen.
   - Saved in the `files/` directory.

2. **Adjacency Matrix**:
   - Exported as `adjacency_matrix.csv` in the `files/` directory.
   - Suitable for network analysis using tools like Gephi.

3. **Network Visualization**:
   - Using the adjacency matrix, visualize voting dynamics and relationships between deputies and candidates in Gephi.

---

## Limitations

- **Dynamic Content**: The project depends on the structure of the Congress website in October 2024. Changes to the site may require updates to the notebook.
- **Manual Execution**: The process is designed for step-by-step execution within the notebook environment.

---

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or feedback, please contact: **[cdberganza](https://github.com/cdberganza)**.
