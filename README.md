# Yelp Sentiment Analysis using Natural Language Processing Modelling

## Description
This project explores the sentiment of [Yelp reviews](https://www.yelp.com/dataset) in the US to provide aggregated insights for restaurant owners, guiding them in decision making to better allocate resources to pinpoint issues and optimize performance.

## Table of contents
To be updated

## Technologies used
This project leverages a variety of technologies, libraries, and tools focused on data science and natural language processing (NLP), built with Python 3.10.6. Here's an overview of the foundational elements:

#### Libraries:
Data Manipulation and Analysis: Pandas for handling and analyzing data structures.
Visualization: WordCloud for generating word clouds, Matplotlib & Seaborn for creating statistical graphics, and Plotly for interactive visualizations.
Machine Learning & NLP: Scikit-learn for machine learning algorithms, NLTK for natural language processing tasks.
Web Application: Streamlit for developing interactive web apps to showcase the NLP models.

#### NLP Techniques and Models:
Topic Modeling: LDA (Latent Dirichlet Allocation) to discover abstract topics within text data.
Text Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency) for converting text to a meaningful vector of numbers.
Predictive Modeling: Linear Regression to predict outcomes based on text data.

#### Development Environment:
Jupyter Notebook: Used for interactive model development and experimentation.
Visual Studio Code: Employed for packaging the model and further development, including the frontend.

#### APIs and External Services:
OpenAI Public API: Engaged to enrich the application with actionable suggestions for restaurant owners through advanced NLP capabilities.

#### Frontend:
Streamlit: Employed a user-friendly interface for interacting with the backend models, facilitating real-time input and feedback from users.

## Project Presentation
[View GoogleSlides Presentation](https://docs.google.com/presentation/d/1Dd6LnDLeSySS5ePxq6UU9FqNN78-lAZCRejmnD34oHk/edit?usp=sharing)

## Key Features of NLPalate
- Generating WordClouds of frequently-mentioned keywords in reviews of reference's restaurant compared with competitors within the same categories in the same city using unsupervised learning algorithm -- term frequency–inverse document frequency (tf-idf)
- Displaying the Top 5 Complaints and Top 5 Compliments that are affecting each restaurant
- Finding the 30 most prevalent topics in all reviews, through topic modelling using Latent Dirichlect Allocation (LDA), and unsupervised machine learning algorithm
- Performing Linear regression to map which topics and having the biggest impact on a restaurant's review score
- Aiding restaurant owners by providing focused and easily digestible recommendations/ suggestions based on the issues/ complaints they received using OpenAI's API

## Web App Demo
[NLPalate](https://nlpalate.streamlit.app/)

## Installation instructions
To be updated

## Usage instructions
To be updated

## Support
For any issues or questions regarding the project, please reach out to me on sophiatsoi.jp@gmail.com 

## Roadmap
Since the project is more of a proof of concept, future plan would be to extend the number of searchable restaurants to make the project practical for restaurant owners.
