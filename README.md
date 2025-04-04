# JavaScript script - Task 1

### Objective
This task create a JavaScript script that manipulates a JSON object and formats the output in a human-readable format. The script processes a list of Wikipedia articles, extracting relevant information and displaying it in a structured format on a webpage.

## Implementation Details
The script extracts data from a JSON array containing article information, including page ID, creation date, and title. It then formats the output as:  
```
Article "ARTICLE TITLE" (Page ID PAGEID) was created at MONTH DAY, YEAR.
```
Example:  
```
Article "André Baniwa" (ID: 6682420) was created on September 13, 2021.
```

### Features
- Reads JSON data containing Wikipedia article information.
- Formats the output to enhance readability.
- Displays the result in a structured, user-friendly format on the webpage.

### Usage  

### Option 1: Directly in Browser

1. Download the `Task_1_Intern.html` file.
2. Open the file in any modern web browser.
3. The script will automatically execute, formatting and displaying the data.


### Option 2: Using a Python HTTP Server

1. Navigate to the directory containing the HTML file.
2. Run the following command:

   `python3 -m http.server 8000`
3. Open your browser and go to:

   `http://localhost:8000/Task_1_Intern.html`

4. The data will be displayed as described.

