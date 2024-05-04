# OnlineFood Analytics

This Jupyter notebook, `analyse.ipynb`, performs detailed analysis on the dataset `onlinefoods.csv`, which consists of various demographic and feedback data collected from an online food ordering platform. The notebook uses Python libraries such as pandas for data manipulation and matplotlib for visualization to extract insights from the data.

## Notebook Structure

The `analyse.ipynb` notebook is structured into several sections, each designed to explore different aspects of the dataset:

### 1. Data Loading
- **Description:** Load the `onlinefoods.csv` into a pandas DataFrame and display the first few entries to understand the structure of the dataset.
- **Libraries Used:** pandas

### 2. Data Overview
- **Description:** Provides a statistical summary of the numerical columns, helping to understand distributions, central tendency, and other statistical elements.
- **Libraries Used:** pandas

### 3. Data Cleaning
- **Description:** Checks for null values across different columns to ensure data quality and readiness for analysis.
- **Libraries Used:** pandas

### 4. Data Segmentation
- **Description:** Segments customers into age groups to facilitate targeted analysis and marketing.
- **Libraries Used:** pandas

### 5. Data Analysis
- **Description:** Includes multiple subsections each aimed at extracting specific insights:
  - **Order Output Analysis:** Counts the occurrences of each unique value in the 'Output' column.
  - **Feedback Analysis:** Analyzes the feedback sentiment from the customers.
  - **Demographic Distribution:** Calculates the relative frequency distributions of gender, marital status, occupation, and education.
- **Libraries Used:** pandas

### 6. Data Visualization
- **Description:** Visualizes various aspects of the data using histograms, pie charts, and bar charts to provide visual insights into age distribution, gender distribution, marital status, and more.
- **Libraries Used:** matplotlib.pyplot

### 7. Geospatial Analysis
- **Description:** Utilizes Folium to generate an interactive map that visualizes the geographical distribution of the data points based on latitude and longitude.
- **Libraries Used:** folium, pandas

## Dataset

The `onlinefoods.csv` file contains the following columns:
- Age
- Gender
- Marital Status
- Occupation
- Monthly Income
- Educational Qualifications
- Family size
- Latitude
- Longitude
- Pin code
- Output
- Feedback

## Usage

To run the `analyse.ipynb` notebook:
1. Ensure that you have Jupyter Notebook installed, or use JupyterLab.
2. Open the notebook in Jupyter and run the cells sequentially to reproduce the analysis.

## Contributing

Contributions to this analysis are welcome. Suggestions to improve the analysis or additional visualizations can be proposed via pull requests.

---

Enjoy exploring the dataset with the provided visualizations and insights in `analyse.ipynb`.
