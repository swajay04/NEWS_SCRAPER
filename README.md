# NEWS_SCRAPER
This project involves scraping news articles from a news website, classifying them based on sections, and storing the data in a CSV file.



## How to Run on Colab
1.Download the NEWS_SCRAPER_CNN.ipynb file (raw)<br />
2.Open Google Colab and click on File<br />
3.Click on Open Notebook <br />
4.Upload the Downloaded notebook and run all cells<br />



 


## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/news-scraping-classification.git
    cd news-scraping-classification
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the scraping script:

    ```bash
    python src/scrape_news.py
    ```

   This script will scrape news articles, classify them, and store the data in the `data/` folder.


## Dependencies

- `requests`: For making HTTP requests.
- `beautifulsoup4`: For parsing HTML content.
- `pandas`: For handling and manipulating data.

## Notes

- Customize the script according to the HTML structure of the news website. (pay special attention to the class attributes of targetted tags)

## Screenshots of Screen 
<img width="1321" alt="image" src="https://github.com/swajay04/NEWS_SCRAPER/blob/main/images/Screenshot%202023-11-22%20123152.png">

<img width="1331" alt="image" src="">

<img width="1330" alt="image" src="">

<img width="1335" alt="image" src="">

<img width="1336" alt="image" src="">

<img width="246" alt="image" src="">






