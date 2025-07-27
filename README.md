# 🎬 IMDb Top 250 Movies Scraper

This project is a Python-based data scraping and analysis notebook that extracts data from the **IMDb Top 250 Movies** page using `BeautifulSoup`, processes it with `pandas`, and prepares it for further exploration or visualization.

## 📌 Project Structure

The Jupyter Notebook is divided into the following tasks:

- **Task 1**: Importing necessary libraries and setting up the environment
- **Task 2**: Sending HTTP requests to IMDb and parsing the HTML
- **Task 3**: Extracting relevant movie data (e.g., title, rank, year, rating)
- *(Additional tasks may include data cleaning, storing in CSV, or visualizations)*

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook / Google Colab
- `requests`
- `BeautifulSoup`
- `pandas`

## 📂 How to Run

1. Open the notebook in Jupyter or Google Colab.
2. Run each cell step-by-step.
3. Ensure you have internet access (IMDb data is scraped live).
4. Required libraries are installed within the notebook (e.g., `!pip install bs4`).

## 📊 Output

The project outputs a structured pandas DataFrame containing:

- Movie Title
- Release Year
- IMDb Rating
- Rank

This can be used for further analysis, visualization, or exporting to CSV.

## 🚀 Future Enhancements

- Add visualizations using `matplotlib` or `seaborn`
- Store the data in a database or cloud storage
- Schedule periodic scraping using cron or Airflow

## 📄 License

This project is for educational and non-commercial use only.

---

*Created by Mahgoub Hany.*
