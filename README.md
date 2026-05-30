# Simple Time Table

A simple HTML project that displays the weekly timetable for the IF4K class using an HTML table with proper formatting and styling.

## 📋 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [File Description](#file-description)
- [Learning Objectives](#learning-objectives)
- [Future Enhancements](#future-enhancements)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## ✨ Features

* Displays the weekly schedule from Monday to Friday
* Includes class timings and subjects with proper organization
* Responsive HTML table with professional formatting
* Advanced HTML table features:
  - `colspan` for spanning multiple columns
  - `rowspan` for spanning multiple rows
  - Table borders and proper alignment
  - Semantic HTML structure
* Shows a recess period common to all weekdays
* Displays Saturday as a holiday
* Clean and readable layout
* Easy to customize and extend

## 🛠️ Technologies Used

* **HTML5** - Semantic markup and table structure
* **CSS** (Optional) - Can be added for enhanced styling

## 📁 Project Structure

```text
simple-Time-table/
│
├── index.html          # Main timetable HTML file
├── README.md           # Project documentation
└── screenshot.png      # (Optional) Screenshot of timetable
```

## 🚀 How to Run

### Method 1: Direct File Opening
1. Download or clone the repository:
   ```bash
   git clone https://github.com/kunalkhillare420/simple-Time-table.git
   ```

2. Navigate to the project folder:
   ```bash
   cd simple-Time-table
   ```

3. Double-click `index.html` or right-click and select "Open with Browser"

### Method 2: Using a Local Server (Recommended)
1. Open a terminal in the project folder
2. Run a simple HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (if http-server is installed)
   http-server
   ```

3. Open your browser and navigate to `http://localhost:8000`

## 📄 File Description

### index.html
The main HTML file containing:
- Proper DOCTYPE and meta tags
- HTML table structure with thead, tbody
- Class schedule data organized by days and time slots
- Proper use of `colspan` and `rowspan` attributes
- Semantic HTML5 elements

### README.md
This file - provides complete project documentation and usage instructions

## 🎓 Learning Objectives

This project demonstrates:

* ✅ Basic HTML5 page structure and semantics
* ✅ Creating and structuring HTML tables
* ✅ Using `rowspan` to merge cells vertically
* ✅ Using `colspan` to merge cells horizontally
* ✅ Formatting and styling table content
* ✅ Organizing and presenting data effectively
* ✅ Writing clean and maintainable HTML code
* ✅ Creating responsive layouts

## 🔮 Future Enhancements

Potential improvements for this project:

- [ ] Add CSS styling for better visual appearance
- [ ] Make the table responsive for mobile devices
- [ ] Add color coding for different subjects
- [ ] Implement interactive features (highlight current class)
- [ ] Add a search/filter functionality
- [ ] Create a dynamic version using JavaScript
- [ ] Add multiple class timetables
- [ ] Include teacher information
- [ ] Add notes or additional details for each class
- [ ] Export timetable to PDF format

## ⚠️ Troubleshooting

### Issue: Table not displaying correctly
- **Solution:** Ensure you're using a modern web browser (Chrome, Firefox, Safari, Edge)
- Check that the HTML file is not corrupted
- Clear browser cache and refresh the page

### Issue: Table looks cluttered
- **Solution:** Consider adding CSS for better styling
- Adjust the HTML structure for better readability
- Use proper spacing and padding

### Issue: Can't open the file
- **Solution:** Right-click the file and select "Open with" to choose a browser
- Alternatively, drag and drop the file into your browser window

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add improvement'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Open a Pull Request

## 📝 License

This project is open source and available for personal and educational use.

## 👨‍💻 Author

**Kunal Khillare**

Feel free to reach out with suggestions, feedback, or questions!

---

**Last Updated:** May 30, 2026
