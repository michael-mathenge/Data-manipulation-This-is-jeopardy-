Jeopardy Data Analysis Project

This repository contains a Python script for analyzing Jeopardy data using the pandas library. The dataset used in this analysis is in a CSV file named "jeopardy.csv". The script performs various data processing tasks and provides insights into the questions and answers in the Jeopardy dataset.

Requirements

Python 3
pandas library
re library (regular expressions)
Getting Started

Clone this repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/your-username/jeopardy-data-analysis.git
Replace "your-username" with your GitHub username.

Install the required Python libraries by running the following command:

Copy code
pip install pandas
Download the "jeopardy.csv" dataset and place it in the project directory.

Project Overview
The main script for data analysis is "script.py". It contains the following functions:

filter_questions_by_words(dataframe, words_list): Filters the dataset for questions containing all the words in a given list.
clean_and_convert_value(value): Cleans and converts the "Value" column to float format.
count_unique_answers(dataframe): Returns the count of unique answers to all questions in a given dataset.
Usage

After cloning the repository and installing the required libraries, run the "script.py" file to perform data analysis on the Jeopardy dataset.
The script will output the average value of questions containing a specific word, as well as the count of unique answers for those questions.
Additionally, the script will compare the number of questions containing the word "Computer" in the 1990s and the 2000s.
Contributing
Contributions to this project are welcome. If you find any issues or want to add new features, please open an issue or create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
The Jeopardy dataset used in this project is sourced from Data World and contains a collection of Jeopardy questions and answers.
