# Trifacta - DATAPRE
#### STEM-Related Job Listings in the Philippines 2021

#### This repository contains the submission files as part of the final project submission for Term 2, AY 2020-2021 in De La Salle University - Manila by the group Trifacta. It includes the documentation, and the notebooks as well as the JSON file.

## Motivation
- As technology continues to advance, more and more companies are turning to technology for their systems from security, to accounting, and now they are also looking at online options when choosing to hire new employees that fit their company and position requirements. While data from physical hiring processes are not readily available to just anyone, online websites display these data openly, and thus are easier to acquire and analyze.
- Many Filipinos find it hard to find a job online due to the steep competition. For their benefit, readily available data from some well known job listings websites were collected for future analysis and research on the hiring trends in the STEM field in the Philippines.

## Scope
The dataset was scraped from the following websites: Monster, PinoyJobs, and Workbank, from the current data that is available from them. There are however some job postings that have not been removed nor updated by the employer that are dated far back and are thus presumed to be still available. The jobs taken were available to Filipino workers with offices that are stationed in the Philippines in the Science, Technology, Engineering, and Mathematics field.

## Data Source
- WorkBank (https://www.workbank.com)
- PinoyJobs (https://pinoyjobs.ph/)
- Monster (https://www.monster.com.ph)
- JobLum (https://ph.joblum.com/)

## Short Definition of Libraries Used
- **os** - a module that provides functions to interact with the operating system.
- **Pandas** - is a tool that helps analyze data.
- **NumPy** - Library that contains multiple functions that help ease the work with arrays, matrices, and alike to better reassemble data.
- **Json** - enables import and export from and to JSON files
- **re** - Short for Regular Expressions, help recognize patterns on strings of data and is used to orderly reassemble them.
- **gensim** - Library that efficiently handles large, unmanaged text collections of data.
- **Nltk** - Short for Natural Language Toolkit. It helps the program to apply human language data to statistical natural language.
- **requests** - Requests allows the program to send HTTP requests easily.
- **Datetime** - An imported module in python to create an object that properly resembles date and time.
- **Seaborn** - A library in python that is used to better visualize data through drawing informative graphs.
- **math** - Imported library that allows quick computations of mathematical tasks
- **gensim.utils simple_preprocess** - used to preprocess text by making them lower-cased, and transforming the words to their original form (de-tokenizing)
- **gensim.parsing.preprocessing STOPWORDS** - stop words are common words that do not have value and are often removed in pre-processing
- **gensim corpora** - used to work with corpus and words
- **gensim models** - used for topic modelling and model training
- **nltk.stem WordNetLemmatizer** - used for grouping similar strings together
- **bs4 BeautifulSoup** - library used to web scrape HTML from websites
- **datetime datetime** - used for converting string of time into datetime format to month, day, and year.
- **datetime timedelta** - used for finding delta of time ago with time scraped if date has minutes, hours, days, or weeks ago
- **dateutil.relativedelta relativedelta** - used for finding delta of time ago with time scraped if date has months and years

## Python Notebook Files Guide

- **Trifacta_WS_Joblum.ipynb** - Web Scraping for Joblum (initial data cleaning was also performed while scraping)
- **Trifacta_WS_Monster.ipynb** - Web Scraping for Monster
- **Trifacta_WS_PinoyJobs.ipynb** - Web Scraping for PinoyJobs
- **Trifacta_WS_Workbank.ipynb** - Web Scraping for Workbank
- **Trifacta_DC_Joblum.ipynb** - Data Cleaning for Joblum
- **Trifacta_DC_Monster.ipynb** - Data Cleaning for Monster
- **Trifacta_DC_PinoyJobs.ipynb** - Data Cleaning for PinoyJobs
- **Trifacta_DC_Workbank.ipynb** - Data Cleaning for Workbank
- **Trifacta_EDA_Compiled.ipynb** - Basic EDA and Compiling Joblum, Monster, PinoyJobs, and Workbank one dataset
- **Trifacta_Jobs_Compiled.ipynb** - All in One 

## How to use
- The notebook with the steps of web-scraping and cleaning are accessible through using Jupyter (https://jupyter.org/install).
- The PDF documentation also grazes on the process of data gathering, data-preprocessing and exploratory data analysis is included for use as reference to those who want to replicate the steps or create their own for other fields.
- The resulting JSON file is also provided in this repository for use for other purposes.

## Usage
The project is readily available to anyone who wishes to use the notebooks as reference, and everyone is welcome to use the data collected for their own projects as long as credit is given.

## Recommendations
It is recommended to widen the scope to other fields and to a wider audience so that there would be more data that are usable for many future works.
The project has already done EDA, however it is further recommended to do more intensive research involving inferences on the data and its variables.
