# IMDb Top 250 Movie Scraper 🎬

## 📌 Project Overview

The IMDb Top 250 Movie Scraper is a Python-based web scraping project that extracts movie information from IMDb's Top 250 Movies chart. It uses Selenium to automate browser interaction and Pandas to organize the collected data and save it as a CSV file.

## 🎯 Objectives

* To collect movie information automatically.
* To extract movie rankings, titles, and ratings.
* To store the collected data in CSV format.
* To understand web scraping and browser automation using Python.

## ✨ Features

* Extracts movie rank, title, and rating.
* Automates browser interaction using Selenium.
* Organizes movie information using Pandas.
* Exports the collected data to a CSV file.
* Supports further data analysis using the CSV output.

## 🛠️ Technologies Used

* **Python** – Programming language
* **Selenium** – Browser automation and web scraping
* **WebDriver Manager** – ChromeDriver management
* **Pandas** – Data organization and CSV export

## 📂 Project Structure

```text
imdb_scraper/
│
├── imdb.py
├── imdb_top_250.csv
└── README.md
```

*Note: The CSV file is generated after a successful run.*

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Folder

```bash
cd imdb_scraper
```

### Step 3: Install Dependencies

```bash
python -m pip install selenium webdriver-manager pandas
```

### Step 4: Run the Project

```bash
python imdb.py
```

If `python` doesn't work on Windows, use:

```bash
py imdb.py
```

## 📊 Output

After successful execution, the project generates an `imdb_top_250.csv` file containing:

| Column | Description                   |
| ------ | ----------------------------- |
| Rank   | Movie's position in the chart |
| Title  | Movie title                   |
| Rating | IMDb movie rating             |

## ⚠️ Important Notes

* An internet connection is required.
* Google Chrome must be installed.
* IMDb may display human verification or restrict automated access. If this happens, manual verification may be required, and the scraper may not work until the movie list loads.
* The CSV file is generated only when the script successfully collects the expected movie data.

## 🚀 Future Enhancements

* Add movie release year and genre.
* Create visualizations of movie ratings.
* Perform exploratory data analysis using Pandas and Matplotlib.
* Develop a simple dashboard to display movie statistics.



## 📄 License

This project is created for educational and learning purposes.
