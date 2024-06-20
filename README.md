## Project Overview

This project is a Python-based web scraper that uses Selenium to scrape the ClearTax website. It verifies GST numbers provided in an Excel file and appends the corresponding business name and registration type to the sheet. The columns to be added can be customized as per the user's requirements.

## Setting Up a Virtual Environment

Before you start, it's recommended to create a virtual environment. This isolates your project and avoids conflicts with other packages. Here's how you can set it up:

# Install virtualenv
```
pip install virtualenv
```
# Navigate to your project directory
```
cd path/to/your/project
```
# Create a new virtual environment
```
virtualenv venv
```
# Activate the virtual environment
```
source venv/bin/activate
```
### On Windows use 
```
`venv\Scripts\activate`
```

## Installing Required Libraries

This project requires certain Python libraries. All the required libraries are listed in the `requirements.txt` file. After activating your virtual environment, you can install these dependencies using pip:

```python3
pip install -r requirements.txt
```
## Customizing the Columns

You can customize the columns that are appended to the Excel sheet by modifying the `notebook.ipynb` file. The relevant code is in the cell where the `df` DataFrame is manipulated.
<br>
<br>
Note : make sure to keep the excel file in the same directory.

