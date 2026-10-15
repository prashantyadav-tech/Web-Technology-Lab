# 🌐 Web Technology Laboratory (BCSL504)

Lab programs for **BCSL504 – Web Technology Laboratory**, V Semester, B.E. Computer Science & Engineering
**Visvesvaraya Technological University (VTU)** | Acharya Institute of Technology

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

---

## 📌 About

This repository contains the solutions to the prescribed programs of the Web Technology Lab.

---

## 📚 List of Programs

| No. | Program | Topics Covered |
|:---:|---------|----------------|
| 1 | Basic HTML tags page | Marquee, headings h1–h6, paragraph, hr, br, blockquote, pre, logical styles (`b`, `u`, `sub`, `sup`) |
| 2 | Class timetable | Table header/footer, rowspan, colspan, cell and row colours |
| 3 | External style sheet | CSS selectors (tag, id, class) on h2, h3, hr, p, div, span, time, img, a |
| 4 | Student registration form | Input types, table alignment, background and font styling |
| 5 | Newspaper page | Semantic elements: header, nav, section, article, aside, figure, table, footer |
| 6 | Simple calculator | Sum, difference, product, quotient, remainder, power, square root, square |
| 7 | JSON / CSV tools | JSON to JS object, JSON date, JSON ⇄ CSV, SHA-256 hash from string |
| 8 | PHP programs | (a) Visitor counter, (b) student records from MySQL sorted with selection sort |
| 9 | jQuery effects | `append()`, `remove()`, `css()`, `animate()` |
| 10 | Ajax examples | XMLHttpRequest, `$.ajax()`, `$.getJSON()`, `JSON.parse()` |

---

## ▶️ How to Run

### Programs 1 – 7 and 9 (HTML / CSS / JavaScript / jQuery)

1. Clone the repository
```bash
   git clone https://github.com/prashantyadav-tech/Web-Technology-Lab.git
```
2. Open the program folder and double-click the `.html` file, or open it with the VS Code **Live Server** extension.

> Programs 3, 5 and 6 use images. Keep them in the same folder as the HTML file.
> Programs 9 and 10 load jQuery from a CDN, so an internet connection is needed.

### Program 8 (PHP + MySQL)

1. Install [XAMPP](https://www.apachefriends.org/) and start **Apache** and **MySQL**.
2. Copy the `08-php-programs` folder into `C:\xampp\htdocs\`.
3. **8a (Visitor counter):** open `http://localhost/08-php-programs/8a-visitor-counter/` in the browser. Visits are counted in `counter.txt`.
4. **8b (Selection sort):**
   - Open `http://localhost/phpmyadmin` and create a database named `students`.
   - Create a `students` table with the columns `id`, `name`, `usn`, `branch`, `email`, `address` and insert some records.
   - Open `http://localhost/08-php-programs/8b-selection-sort/`.

### Program 10 (Ajax)

Ajax requests do not work when a page is opened directly from the file system. Run it through a local server:

```bash
# from inside the 10-ajax folder
python -m http.server 8000
```

Then open `http://localhost:8000` in the browser. The folder must contain `textfile.txt` and `data.json`.

---

## 🛠️ Tools Used

- VS Code
- Google Chrome / any modern browser
- XAMPP (Apache, MySQL, PHP)
- Git & GitHub

---

## 📝 Note

These programs were written for academic purposes as part of the VTU BCSL504 lab curriculum. Feel free to refer to them for learning, but try writing your own first. 😊