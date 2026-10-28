# Demographic Data Analyzer

A Python data analysis project developed as part of the freeCodeCamp *Data Analysis with Python* certification. This program utilizes **Pandas** to extract, clean, and analyze demographic data from the 1994 Census database.

---

## Key Features & Questions Answered

* **Race Distribution:** Counts the total representation of each race in the dataset.
* **Gender Demographics:** Computes the average age of men.
* **Educational Attainment:** Calculates the percentage of individuals holding a Bachelor's degree.
* **Advanced Education vs. Salary:** Determines the percentage of people with advanced degrees (`Bachelors`, `Masters`, or `Doctorate`) who earn more than $50K annually, compared to those without advanced education.
* **Work Hours Analysis:** Finds the minimum number of hours worked per week and calculates the percentage of minimum-hour workers earning >$50K.
* **Global Wealth Distribution:** Identifies the country with the highest percentage of high-earning individuals (>50K) and calculates that exact percentage.
* **Regional Insights:** Identifies the most popular occupation for high earners in India.

---

## Tech Stack

* **Language:** Python
* **Library:** Pandas
* **Testing:** Unittest framework

---

## Project Structure

* `demographic_data_analyzer.py`: Contains the core data processing logic and calculation functions.
* `main.py`: Entry point script used to run and test the program locally.
* `test_module.py`: Official unit test suite validating function outputs.
* `adult.data.csv`: The underlying demographic dataset.
