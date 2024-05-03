# COMP 3612 (Fall 2021)
## Assignment #2: Single-Page Application (SPA) Overview: Shakespeare's Plays

#### Part of the design had to adhere to instructor specifications.
**Please view `COMP3612 Assignment 2.pdf` for full technical requirements.**

---

### Overview:
This assignment involves developing a single-page application (SPA) named `index.html` that allows users to explore Shakespeare's plays through a dynamic and interactive interface.

### Main Features:
- **Single HTML Page:** The entire application must be hosted on a single HTML page called `index.html`.
- **Two Main Views:** The application has two main views: "List of Plays" and "Play Text." The "List of Plays" view is the default view on startup.

### List of Plays View:
- **Data Source:** Play data is stored in a `plays.json` file, which includes titles, composition dates, and additional metadata.
- **Functionality:**
  - Display an unordered, scrollable list of plays sorted by name or composition date.
  - Allow users to sort plays and refresh the list accordingly.
  - Show play details on selection, including title, date, genre, links to additional resources, and synopsis.
  - Highlight selected play for visual feedback.
  - Provide a button to view play text, hidden if no text is available.

### Play Text View:
- **API Fetching:** Fetch play text from an external API when the "View Play Text" button is clicked.
- **Interactive Elements:** Enable users to filter the play text by scene and highlight specific words or phrases within the text.
- **Data Handling:** Use local storage to cache fetched play data for improved performance.

### Additional Features:
- **Credits Display:** Include a header icon labeled "Credits" that displays the developer's name and course information when hovered over.
- **Styling:** Preliminary styling and markup are provided, with expectations to enhance these using the provided CSS.

### Requirements:
- **JavaScript Usage:** Custom JavaScript is required. The use of jQuery, Bootstrap, or other third-party libraries is prohibited. Small snippets of online JavaScript code may be used if properly credited within the code.

### Performance Optimization:
- **Caching:** Implement caching of play data using local storage to reduce API requests and enhance load times.

---
