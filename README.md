# Personal Job Recommender (Ongoing...)


Welcome to the Personal Job Recommender repository! This project is designed to assist job seekers in finding relevant job opportunities by leveraging web scraping techniques and natural language processing (NLP) algorithms.

## Overview

This project utilizes Python, Selenium, BeautifulSoup (bs4), NLTK, Gensim, and Word2Vec to create a personalized job recommendation system. It scrapes job listings from LinkedIn, processes the job descriptions, and trains a Word2Vec model to understand the context of the job descriptions. When provided with a candidate's description, the system recommends jobs that match the candidate's skills and interests.

## Features

- Web scraping LinkedIn job listings with Selenium and BeautifulSoup.
- Preprocessing job descriptions using NLTK.
- Training a model using TF-IDF weighted Word2Vec and Transfer Learning from gensim.
- Generating personalized job recommendations based on a candidate's profile.

## Technologies Used
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) [![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)](https://www.selenium.dev/) [![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-59666C?style=for-the-badge&logo=beautifulsoup&logoColor=white)](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) [![NLTK](https://img.shields.io/badge/NLTK-3476AB?style=for-the-badge&logo=nltk&logoColor=white)](https://www.nltk.org/) [![Gensim](https://img.shields.io/badge/Gensim-46C71C?style=for-the-badge&logo=gensim&logoColor=white)](https://radimrehurek.com/gensim/)
-  Selenium: A powerful tool for automating web browsers, essential for scraping dynamic web content like LinkedIn job listings.
-  BeautifulSoup (bs4): A Python library for pulling data out of HTML and XML files, used for parsing scraped web content.
-  NLTK: Natural Language Toolkit, a library for building NLP applications, used for text preprocessing.
-  Gensim: A Python library for topic modeling, document indexing, and similarity retrieval with large corpora, used for training Word2Vec models.

## Usage (WILL BE CHANGED)

Run `job_parsing.ipynb` to create the dataset, and then `job_vectors.ipynb` to train the model. You will need to change some lines (for now).
