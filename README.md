# When Merged - Professional File Comparison Tool (Web Interface)

This `index.html` file is the single-page web interface for "When Merged", a professional file comparison tool. It provides a user-friendly UI for uploading, managing, and comparing text-based files directly in the browser.

## Features

*   **File Management:**
    *   Upload multiple files using a file input or an "Add Files" button.
    *   View a list of added files with their detected types (e.g., TXT, JSON, XML, CSV).
    *   Select and remove specific files.
    *   Clear all added files.
    *   File count display.
*   **Comparison Views:**
    *   **Text Comparison:**
        *   Side-by-side or stacked (responsive) diff view.
        *   Highlights added, removed, and changed lines.
        *   Syntax highlighting for JSON and XML.
        *   Line numbers for easy reference.
    *   **Table View (for CSV files):**
        *   Compares CSV files row by row, based on a key (first column).
        *   Highlights added, removed, and changed rows.
        *   Highlights specific changed cells within rows.
        *   Side-by-side table display.
    *   **Summary View:**
        *   Provides a detailed report including file statistics (name, type, size, line count, word count) and comparison analysis (additions, removals, changes).
*   **Difference Navigation:**
    *   "Previous Difference" and "Next Difference" buttons to easily jump between changes.
    *   A counter displays the current difference number and total differences.
*   **User Interface:**
    *   Responsive design adapting to different screen sizes.
    *   Collapsible sidebar for file management.
    *   Tabbed interface to switch between Text Comparison, Table View, and Summary.
    *   Status bar displaying current status (e.g., Ready, Loading, Comparison completed) and a real-time clock.
    *   Notification messages for user feedback (success, error, info, warning).
    *   Visually distinct color-coding for different types of changes (added, removed, changed, current diff, unchanged).
*   **Technology:**
    *   Built with HTML, CSS (Tailwind CSS via CDN), and vanilla JavaScript.
    *   Client-side file reading and comparison.

## How to Use

1.  Open `index.html` in a modern web browser.
2.  Use the "Add Files" button or the file input in the left panel to select at least two files for comparison.
3.  Once files are added, click the "COMPARE FILES" button.
4.  Results will be displayed in the right panel. Use the tabs (Text Comparison, Table View, Summary) to explore the differences.
5.  Use the "◀" and "▶" buttons to navigate through detected differences.