# Reports and Publications

A web application for browsing and filtering reports and publications using filters and search.

## Features

- Filter reports by type and year range
- Search reports by title
- Pagination support
- Responsive design with GC Web theme

## Files

- `index.html` - Main HTML structure
- `script.js` - Application logic (jQuery-based)
- `style.css` - Custom styles
- `clean_reports.json` - Reports data

## Setup

1. Clone this repository
2. Serve the files using a local server (e.g., `python -m http.server 8000`)
3. Open `http://localhost:8000` in your browser

## Data Structure

Reports in `clean_reports.json` should have:
- `title` - Report title
- `type` - Report type/category
- `year` - Year of publication
- `link` - URL to the report
