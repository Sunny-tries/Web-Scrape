# Largest Companies in the United States by Revenue Analysis

This Jupyter Notebook project demonstrates a complete workflow for web scraping using Python. It extracts data on the largest companies in the United States by revenue from Wikipedia and processes this information to create a structured CSV file. This project is an excellent showcase of integrating BeautifulSoup for web scraping, pandas for data manipulation, and Jupyter Notebook as the development environment.

## Project Overview

The goal of this project was to scrape data from a Wikipedia page listing the largest companies in the United States by revenue. This involved:
- Fetching the webpage content using `requests`.
- Parsing the HTML content and extracting data using `BeautifulSoup`.
- Cleaning and structuring the data with `pandas`.
- Saving the cleaned data into a CSV file for further analysis or visualization.
- Website used: https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue

## Tools and Libraries Used

- **BeautifulSoup**: For parsing HTML and extracting the required information.
- **requests**: To make HTTP requests to the Wikipedia page.
- **pandas**: Used for creating and manipulating the DataFrame to structure the scraped data.
- **Jupyter Notebook**: An interactive environment that was used to write, test, and document the code.

## Key Learnings

- **Web Scraping with BeautifulSoup**: Learned how to navigate and parse HTML documents, extract specific elements, and manipulate HTML tags to get the needed data.
- **Data Manipulation with pandas**: Gained experience in data cleaning, structuring data into DataFrames, and transforming data for analysis purposes.
- **Jupyter Notebook Proficiency**: Developed skills in using Jupyter Notebooks for writing Python code in an interactive environment, which is ideal for data analysis and exploratory data analysis (EDA).

## Project Files

- **Largest_Companies_Analysis.ipynb**: The Jupyter Notebook containing all the code, comments, and explanations for the project.
- **Companies.csv**: The output CSV file containing the structured data on the largest companies in the United States by revenue, extracted from Wikipedia.

## Future Directions

- **Integration with Tableau**: To enhance the visualization of the data, I plan to use Tableau to create interactive dashboards. This will allow for better storytelling with the data, enabling viewers to engage with the information in a dynamic way. By connecting the CSV file as a data source in Tableau, I can construct visualizations that highlight key trends, comparisons, and insights about the largest companies by revenue.
- **Advanced Analysis with SQL**: To deepen the analysis, incorporating SQL could facilitate more complex queries and aggregations. For instance, by importing the data into a SQL database, I can perform advanced analytical queries, such as calculating growth rates over time or segmenting companies by industry more efficiently. This step would also streamline the analysis process for larger datasets and support integration with other data sources for a more comprehensive analysis.

## How to Use

1. Ensure you have Python installed along with the required libraries (`BeautifulSoup`, `requests`, `pandas`).
2. Open the `Largest_Companies_Analysis.ipynb` file in Jupyter Notebook to view the project.
3. Run the cells sequentially to see each step of the web scraping process, data manipulation, and the final output.
4. The output CSV file `Companies.csv` will be saved to the specified path. You can open it with any spreadsheet software for further analysis or visualization.

## Conclusion

This project was a comprehensive introduction to the practical applications of web scraping, data cleaning, and manipulation using Python. Through the process, I was able to learn and apply the fundamentals of BeautifulSoup for web scraping, pandas for data analysis, and the versatility of Jupyter Notebook as a tool for developing and presenting data analysis projects.
