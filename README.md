# Google Sheets Clone

## Overview
This project is a web-based spreadsheet application that mimics the functionality of Google Sheets. It allows users to enter and manipulate data in a grid format, apply formulas, perform text styling, and visualize data using charts. The application is built using HTML, CSS, and JavaScript and supports features such as row/column additions, drag selection, keyboard navigation, and data validation.

## Features
### Spreadsheet Features:
- **Dynamic Grid Creation**: Generates a 64x64 spreadsheet grid on page load.
- **Editable Cells**: Users can enter text, numbers, and formulas.
- **Formula Bar**: Allows users to enter formulas like `=SUM(A1:A5)`, `=AVERAGE(A1:A5)`, etc.
- **Auto Save & Load**: Users can save the spreadsheet data and load it from an uploaded file.
- **Drag Selection**: Allows selection of multiple cells by clicking and dragging.
- **Drag and Drop**: Enables moving data between cells.
- **Keyboard Navigation**: Supports `Shift + Arrow keys` for selection and `Enter` for next cell movement.
- **Text Styling**: Users can apply **bold**, *italic*, and underline styles.
- **Text Color Change**: Users can change text colors using a color picker.
- **Row and Column Addition**: Dynamically add rows and columns to the spreadsheet.

### Formulas Supported:
- **Basic Mathematical Operations**: `=SUM(A1:A5)`, `=AVERAGE(A1:A5)`, `=MAX(A1:A5)`, `=MIN(A1:A5)`, `=COUNT(A1:A5)`
- **Text Manipulation**: `=UPPER(A1)`, `=LOWER(A1)`, `=TRIM(A1)`, `=REMOVE_DUPLICATES(A1:A5)`, `=FIND_AND_REPLACE(old,new,A1:A5)`
- **Date Functions**: `=DATE(YYYY,MM,DD)`, `=TODAY()`, `=NOW()`

### Data Visualization:
- **Chart Creation**: Users can generate a chart based on selected data.

### LINK TO RUN THE PROJECT:  http://localhost:8000:
            This projects can able to run only in the localhost

### Testing:
- **Automated Formula Testing**: Runs test cases on formulas and saves test results in an Excel file.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Libraries**:
  - [Chart.js](https://cdn.jsdelivr.net/npm/chart.js) - for data visualization
  - [XLSX.js](https://cdn.jsdelivr.net/npm/xlsx/dist/xlsx.full.min.js) - for exporting and importing spreadsheets

## File Structure
```
📂 Google Sheets Clone
├── index.html     # Main structure of the spreadsheet interface
├── script.js      # JavaScript logic for spreadsheet functionality
├── styles.css     # Styles for formatting and layout
```

## Installation & Usage
### 1. Clone the Repository
```bash
git clone https://github.com/your-repo/google-sheets-clone.git
cd google-sheets-clone
```

### 2. Open in Browser
Simply open `index.html` in any modern browser (Chrome, Firefox, Edge, etc.).

### 3. Features Walkthrough
- Click on any cell and enter values or formulas.
- Use the toolbar for text styling and adding rows/columns.
- Use the formula bar to enter formulas like `=SUM(A1:A5)`.
- Click `Create Chart` to generate a chart from selected data.
- Click `Save Spreadsheet` to download the data.
- Upload a file to load spreadsheet data.

## Future Enhancements
- **Multi-user collaboration**
- **Database storage for persistence**
- **Advanced formula support**
- **Enhanced UI/UX improvements**

## Contributors
- **Your Name** - Varshini Durai Rasu


