# Netflix Data Analysis Using MS SQL

This repository contains the code and results of my analysis of Netflix data obtained from Kaggle. The goal of this project is to explore, clean, and analyze the dataset using Microsoft SQL Server (MS SQL) to extract meaningful insights and trends about the content available on Netflix.

## Dataset

The dataset used in this project is sourced from Kaggle and includes information about Netflix movies and TV shows, such as titles, genres, release dates, duration, ratings, and more.

## Project Structure

- `data/`: Contains the original dataset.
- `sql_scripts/`: SQL scripts for data cleaning, transformation, and analysis.
- `results/`: Exported reports and visualizations generated from the analysis.
- `README.md`: Project overview and description.

## Analysis Workflow

1. **Data Loading**:
    - Importing the dataset into MS SQL Server.

2. **Data Cleaning**:
    - Handling missing values
    - Standardizing column names
    - Removing duplicates
    - Data type conversion

3. **Data Transformation**:
    - Creating new columns for detailed analysis (e.g., extracting year from release date)
    - Aggregating data for summary statistics

4. **Exploratory Data Analysis (EDA)**:
    - Distribution of movies and TV shows over the years
    - Analysis of genres and their popularity
    - Top directors, actors, and countries producing Netflix content
    - Duration analysis of movies and TV shows
    - Rating distribution and analysis

5. **Visualizations**:
    - Generating visualizations using SQL Server Reporting Services (SSRS) or exporting data for visualization in tools like Tableau or Power BI

## Tools and Technologies

- Microsoft SQL Server (MS SQL)
- SQL Server Management Studio (SSMS)
- SQL Server Reporting Services (SSRS)
- Tableau / Power BI (optional for advanced visualizations)

## Results

The analysis reveals interesting trends and patterns in Netflix content, such as the increase in the number of original productions over the years, the dominance of certain genres, and the geographical distribution of Netflix content.

## Conclusion

This project provides a comprehensive overview of the Netflix dataset and demonstrates the use of various data analysis techniques in MS SQL to extract valuable insights. The findings can be useful for understanding the content strategy of Netflix and identifying trends in the entertainment industry.

## How to Use

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/netflix-data-analysis-ms-sql.git
    ```
2. Navigate to the project directory:
    ```sh
    cd netflix-data-analysis-ms-sql
    ```
3. Import the dataset into your MS SQL Server instance.
4. Run the SQL scripts in the `sql_scripts/` directory to clean, transform, and analyze the data.
5. Optionally, use SSRS or other visualization tools to generate reports and visualizations.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## License

This project is licensed under the MIT License.

---

Feel free to customize this description according to your specific analysis and findings.
