

---

# Mars Data Analysis Project

## Overview

Welcome to the Mars Data Analysis Project. This project involves performing web scraping and data analysis on Mars-related data using Python, Splinter, BeautifulSoup, and Pandas. The project is divided into two main parts: scraping Mars news articles and analyzing Mars weather data.

## Project Structure

The project repository contains the following files and directories:

- `part_1_mars_news.ipynb`: Jupyter notebook containing the code to scrape titles and preview text from Mars news articles.
- `part_2_mars_weather.ipynb`: Jupyter notebook containing the code to scrape and analyze Mars weather data.
- `mars_weather_data.csv`: CSV file containing the analyzed Mars weather data.

## Data Analysis

### Mars News Scraping

This task involves scraping the latest news articles related to Mars from the NASA Mars News site. The steps include:
- Using Splinter to automate browsing and BeautifulSoup to parse the HTML content.
- Extracting the titles and preview text of the news articles.
- Storing the results in a list of dictionaries.

### Mars Weather Analysis

This analysis involves scraping and analyzing Mars weather data from a table on the Mars Temperature Data Site. The steps include:
- Extracting the HTML table into a Pandas DataFrame.
- Converting data types for accurate analysis.
- Analyzing the average minimum temperature and atmospheric pressure by month.
- Estimating the length of a Martian year in terrestrial (Earth) days.

![Mars Weather Analysis](/pic.png)

## Instructions for Running the Project

1. **Clone the Repository**:
   ```bash
   git clone <your-repository-url>
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd mars-data-analysis
   ```
3. **Set Up the Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # For MacOS/Linux
   venv\Scripts\activate      # For Windows
   ```
4. **Install the Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
5. **Run the Jupyter Notebooks**:
   - Open Jupyter Notebook and run `part_1_mars_news.ipynb` to scrape Mars news data.
   - Run `part_2_mars_weather.ipynb` to scrape and analyze Mars weather data.

6. **Explore the Results**:
   - Review the Mars weather data in the `mars_weather_data.csv` file.
   - Check the visualizations generated in the notebooks.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

If you have any questions or feedback, please feel free to reach out at [Luis.Llamas@maslla.com](mailto:Luis.Llamas@maslla.com).

---

Thank you for exploring this project. Happy coding!

---

