

# Job Data Collection and Analysis Using APIs

## Project Overview
This project demonstrates how to interact with APIs to collect job postings data, analyze it, and save the results into an Excel spreadsheet. The focus is on fetching data for various technologies and programming languages using a Flask-based API and Python libraries.

## Features
1. **API Interaction**: Fetch job postings data using both GET and POST requests from a provided API endpoint.
2. **Data Filtering**: Filter job postings based on specific technologies (e.g., Python, Java, SQL).
3. **Excel Integration**: Write the collected data into an Excel file for easy storage and analysis.
4. **Error Handling**: Includes robust error handling for API responses and data processing.

## Technologies Used
- **Python**: For data fetching, processing, and Excel file creation.
- **Flask**: To serve the API and provide job data.
- **openpyxl**: For working with Excel spreadsheets.
- **Requests**: For HTTP GET and POST requests.

## Steps
1. **Fetch Job Data**: Retrieve job data for specified technologies using the API.
2. **Process Data**: Filter the data based on the selected technologies.
3. **Save Data to Excel**: Store the filtered data into an Excel spreadsheet (`job-postings.xlsx`).
4. **Analyze Results**: Use the saved data for further analysis or visualization.

## How to Run
1. Install required libraries:
   ```bash
   pip install flask requests openpyxl
   ```
2. Run the Flask API in your environment:
   ```python
   python api.py  # Replace with your Flask file if applicable
   ```
3. Run the main data collection script to fetch data and save it to an Excel file.

## Output
- The project generates an Excel file (`job-postings.xlsx`) containing job counts for each specified technology:
  - Technologies: Python, Java, C++, SQL, MongoDB, and more.
  - Columns: `Technology`, `Job Count`.

## Future Enhancements
- Add data visualization (charts/graphs) for better insights.
- Implement pagination for API calls if the dataset is large.
- Support for additional output formats (e.g., CSV, JSON).



