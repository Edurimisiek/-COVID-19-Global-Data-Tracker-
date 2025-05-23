# COVID-19 Global Trends Analysis

## Description
This project analyzes global COVID-19 trends, including cases, deaths, recoveries, and vaccinations across countries over time. Using Python data tools, the project involves data cleaning, exploratory data analysis (EDA), and visualization to generate insights. The final deliverable is a well-documented Jupyter Notebook with visualizations and narrative insights, suitable for presentation or publishing.

## Objectives
- **Import and Clean Data**: Load and preprocess the Our World in Data COVID-19 dataset.
- **Analyze Trends**: Examine time trends for cases, deaths, and vaccinations.
- **Compare Metrics**: Compare metrics across selected countries (Kenya, USA, India).
- **Visualize Data**: Create line charts, bar charts, and a choropleth map to visualize trends.
- **Communicate Insights**: Summarize findings in a narrative report within a Jupyter Notebook.

## Tools and Libraries
- **Jupyter Notebook**: For interactive development and documentation.
- **Python Libraries**:
  - `pandas`: Data loading, cleaning, and analysis.
  - `matplotlib` & `seaborn`: Line and bar chart visualizations.
  - `plotly`: Interactive choropleth map.
- **Dataset**: Our World in Data COVID-19 dataset (`owid-covid-data.csv`).

## How to Run/View the Project
1. **Prerequisites**:
   - Install Python 3.8+.
   - Install required libraries:
     ```bash
     pip install pandas matplotlib seaborn plotly
     ```
   - Download the dataset from [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv) or use the direct URL in the code.

2. **Setup**:
   - Clone this repository or copy the Jupyter Notebook (`covid_analysis.ipynb`) to your local machine.
   - Place the `owid-covid-data.csv` file in the same directory as the notebook (if not using the URL).

3. **Run the Notebook**:
   - Open Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `covid_analysis.ipynb` and run all cells sequentially.
   - Ensure an internet connection for the Plotly choropleth map to render.

4. **View Outputs**:
   - The notebook includes code, visualizations (line charts, bar charts, choropleth map), and a narrative report.
   - Export the notebook to PDF via `File > Download as > PDF via LaTeX` (requires LaTeX installation) or to HTML and print to PDF.
   - For presentations, take screenshots of visualizations and add them to PowerPoint with narrative text.

## Insights and Reflections
- **Key Observations**:
  - The United States consistently showed the highest cumulative cases and deaths among the selected countries, reflecting its large population and early pandemic impact.
  - Vaccination rates varied significantly, with wealthier nations like the USA achieving higher coverage compared to Kenya.
  - The choropleth map highlighted global disparities, with high case densities in North America and parts of Asia.
- **Challenges**:
  - Handling missing data required assumptions (e.g., filling with zeros), which could skew some metrics. Interpolation might be explored for more accuracy.
  - The dataset’s size demanded efficient filtering to focus on specific countries for smoother analysis.
- **Reflections**:
  - This project underscored the power of data visualization in revealing public health trends and disparities.
  - Future iterations could include advanced metrics (e.g., case fatality rates by age group) or predictive modeling to forecast trends.
  - The process highlighted the importance of clear documentation for reproducibility and stakeholder communication.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Dataset provided by [Our World in Data](https://ourworldindata.org/coronavirus).
- Built with Python, pandas, matplotlib, seaborn, and plotly.
