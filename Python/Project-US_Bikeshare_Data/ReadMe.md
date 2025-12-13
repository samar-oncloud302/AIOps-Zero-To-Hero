# 🚴 Python Project: Explore US Bike Share Data

## 📌 Overview

This project analyzes bike share data from three major U.S. cities—**Chicago**, **New York City**, and **Washington**—using **Python**, **NumPy**, and **pandas**. The goal is to compute descriptive statistics and create an **interactive terminal experience** for users to explore the dataset.

I would:

*   Import and clean data.
*   Compute key statistics (popular travel times, stations, trip durations, user demographics).
*   Build an interactive script that responds to user input.

## 📂 Project Files

*   **bikeshare.py** – Main Python script for analysis and user interaction.
*   **chicago.csv**, **new\_york\_city.csv**, **washington.csv** – City datasets.
*   **all\_project\_files.zip** – Contains all required files.

## ✅ Features

*   **Interactive CLI**:
    *   Choose city, month, and day filters.
    *   View popular travel times, stations, and trip combinations.
    *   Display user demographics and trip duration stats.
    *   Option to view raw data in chunks of 5 rows.
*   **Robust Input Handling**:
    *   Handles invalid inputs gracefully.
*   **Data Analysis**:
    *   Uses pandas for filtering, grouping, and descriptive statistics.

## 🛠️ Technologies Used

*   **Python 3**
*   **NumPy**
*   **pandas**

## 📊 Statistics Computed

1.  **Popular Times of Travel**
    *   Most common month, day, and start hour.
2.  **Popular Stations and Trips**
    *   Most common start station, end station, and trip combination.
3.  **Trip Duration**
    *   Total and average travel time.
4.  **User Info**
    *   Counts of user types and gender.
    *   Earliest, most recent, and most common birth year.

## ▶️ How to Run

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/bikeshare-analysis.git
    cd bikeshare-analysis
    ```
2.  Ensure Python 3 and required libraries are installed:
    ```bash
    pip install pandas numpy
    ```
3.  Run the script:
    ```bash
    python bikeshare.py
    ```
4.  Follow the prompts to explore the data interactively.

## 📌 Example Interaction

    Hello! Let's explore some US bikeshare data!
    Please enter a city (chicago, new york city, washington): chicago
    Please enter a month (january to june) or 'all': march
    Please enter a day of the week or 'all': friday

    Calculating The Most Frequent Times of Travel...
    The most common month: 3
    The most common day of week: Friday
    Most Common Start Hour: 17

## 🧪 Project Requirements

*   Python 3.x
*   pandas
*   NumPy
*   Terminal or command-line interface

## 📖 Learning Outcomes

*   Data wrangling and cleaning.
*   Using pandas for data analysis.
*   Building interactive scripts.
*   Handling user input and errors gracefully.

## 🔗 Resources

*   Udacity Programming for Data Science with Python
*   pandas Documentation
*   NumPy Documentation
