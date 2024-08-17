# web-scraping
A Python script that scrapes the list of courses being offered by different colleges in India. This script takes either the name of the college or the URL of the college's course page as input and return a list of all courses offered by that college.

# Course Scraper Script
## Overview

This script is designed to scrape course offerings from a CSV file containing information about various colleges. It processes the data to filter out irrelevant rows, cleans up the course information, and provides a summary of the courses available at each college.

## Requirements

- Python 3.x
- Pandas
- Matplotlib

You can install the required packages using pip:

```bash
pip install pandas matplotlib

```

# Script Usage
## Prepare the CSV File
Ensure that you have a CSV file with columns named College Name, Course Number, and Course Name. The file should be formatted correctly with these columns.

## Save the Script

Save the Python script to a file, e.g., main.py

## Run the Script
Execute the script from the command line:

```bash
python main.py
```

## Assumptions

- The CSV file is correctly formatted with columns `College Name`, `Course Number`, and `Course Name`.
- Course numbers are numeric or can be coerced into numeric values.
- Course names are not empty or irrelevant.
- The script assumes that there are no duplicate entries for the same course.

## Limitations

- The script does not handle missing or incorrect data beyond basic filtering.
- It assumes that the CSV file is well-formed and does not contain any unexpected formats or characters.
- The visualization will be basic; more sophisticated visualizations may require additional libraries or custom code.

## Future Enhancements

- Handle more complex data formats or additional fields.
- Improve error handling and data validation.
- Enhance visualizations for better insights.
