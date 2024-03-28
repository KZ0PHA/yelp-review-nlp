# Yelp Sentiment Analysis using Natural Language Processing Modelling

## Table of contents
- [Description](#description)
- [Technologies Used](#technologies-used)
  - [Libraries](#libraries)
  - [NLP Techniques and Models](#nlp-techniques-and-models)
  - [Development Environment](#development-environment)
  - [APIs and External Services](#apis-and-external-services)
  - [Frontend](#frontend)
- [Project Presentation](#project-presentation)
- [Key Features of NLPalate](#key-features-of-nlpalate)
- [Web App Demo](#web-app-demo)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
- [Support](#support)
- [Roadmap](#roadmap)

## Description
This project explores the sentiment of [Yelp reviews](https://www.yelp.com/dataset) in the US to provide aggregated insights for restaurant owners, guiding them in decision making to better allocate resources to pinpoint issues and optimize performance.

## Technologies used
This project leverages a variety of technologies, libraries, and tools focused on data science and natural language processing (NLP), built with Python 3.10.6. Here's an overview of the foundational elements:

### Libraries:
Data Manipulation and Analysis: Pandas for handling and analyzing data structures.
Visualization: WordCloud for generating word clouds, Matplotlib & Seaborn for creating statistical graphics, and Plotly for interactive visualizations.
Machine Learning & NLP: Scikit-learn for machine learning algorithms, NLTK for natural language processing tasks.
Web Application: Streamlit for developing interactive web apps to showcase the NLP models.

### NLP Techniques and Models:
Topic Modeling: LDA (Latent Dirichlet Allocation) to discover abstract topics within text data.
Text Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency) for converting text to a meaningful vector of numbers.
Predictive Modeling: Linear Regression to predict outcomes based on text data.

### Development Environment:
Jupyter Notebook: Used for interactive model development and experimentation.
Visual Studio Code: Employed for packaging the model and further development, including the frontend.

### APIs and External Services:
OpenAI Public API: Engaged to enrich the application with actionable suggestions for restaurant owners through advanced NLP capabilities.

### Frontend:
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
To get this project up and running on your local machine, follow these steps. These instructions assume you have Python 3.10.6 installed. If not, please install Python from python.org first.

### 1. Clone the Repository
Start by cloning the repository to your local machine. Open a terminal and run:
```bash
git clone https://github.com/yourusername/yelp-sentiment-analysis.git
cd yelp-sentiment-analysis
```
Replace https://github.com/yourusername/yelp-sentiment-analysis.git with the actual URL of your GitHub repository.

### 2. Setting Up a Virtual Environment with pyenv
It's recommended to manage Python versions and virtual environments using pyenv. This ensures that project dependencies do not interfere with system-wide Python packages. If you haven't already, install pyenv by following the instructions on pyenv's GitHub repository.

After installing pyenv, follow these steps to set up a virtual environment for the project:
##### 1. Install Python 3.10.6 using pyenv (skip this step if you already have this version installed):
```bash
pyenv install 3.10.6
```
##### 2. Create a virtual environment named yelp-sentiment-analysis (or another name of your choice) using Python 3.10.6:
```bash
pyenv virtualenv 3.10.6 yelp-sentiment-analysis
```
##### 3. Activate the virtual environment. Navigate to your project's directory, then set the local Python version to your newly created virtual environment:
```bash
cd path/to/yelp-sentiment-analysis
pyenv local yelp-sentiment-analysis
```
This step will create a .python-version file in your project directory, automatically activating the yelp-sentiment-analysis virtual environment whenever you navigate to this directory.
##### 4. Verify that the virtual environment is activated by checking the Python version:
```bash
python --version
```
This command should output Python 3.10.6, indicating that the correct version of Python is being used.

### 3. Install Dependencies
Install all the dependencies listed in requirements.txt:
```bash
pip install -r requirements.txt
```
Ensure you have a requirements.txt file in your repository with all the necessary libraries, including Pandas, WordCloud, Matplotlib, Seaborn, Plotly, Scikit-learn, NLTK, and Streamlit.

### 4. Set Up the Streamlit Application
To run the Streamlit application, navigate to the directory containing your Streamlit script (e.g., app.py) and execute:
```bash
streamlit run app.py
```

### 5. Accessing OpenAI API
To use the OpenAI Public API, you need an API key. Please visit OpenAI API for instructions on how to obtain one. Once you have your API key, ensure you store it securely and use it to authenticate your API requests as per OpenAI's documentation.
```bash
streamlit run app.py
```

## Support
For any issues or questions regarding the project, please reach out to me on sophiatsoi.jp@gmail.com 

## Roadmap
Since the project is more of a proof of concept, future plan would be to extend the number of searchable restaurants to make the project practical for restaurant owners.
