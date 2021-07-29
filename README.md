# Statistical analysis of hr characteristics of a company

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There are no specific requirements to run and explore this project. Python 3.8.10 and current versions (as of 29/07/2021) of the following libraries were used:
- requests
- BeautifulSoup
- time
- pandas
- json

## Project Motivation<a name="motivation"></a>

Using web scraping I wanted to extract information form different websites using two main approaches:
1. Using BeautifulSoup through inspection of page's source code (websites used: https://habr.com/ru/all/ and https://www.avast.com/hackcheck/).
2. Using API (https://vk.com/)

## File Descriptions <a name="files"></a>

There is 1 notebook available above which explores the above mentioned web scraping techniques.
There is also a file that contains token for vk API, though for security reasons it is not included on github and has to be created separately if anyone wishes to run the API part of the notebook.

## Results<a name="results"></a>

All findings are presented within the notebook for better visibility and context.
It is worth mentioning that https://www.avast.com/hackcheck uses a hidden API which is used to check email for hacks and not its own database.

## Licensing, Authors, Acknowledgments<a name="licensing"></a>

Credit goes to https://habr.com/ru/all/ and https://www.avast.com/hackcheck for not making it impossible to use web scraping on their websites. Also, to https://vk.com/ for providing free access to their API.
Feel free to download or fork the code and explore it in any way you would like.# web_scraping_beautifulsoup_api_vk
