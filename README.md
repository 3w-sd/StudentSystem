# Student Result Inquiry System

A simple, client-side web application for students to check their academic results. This system allows users to enter their ID, select their major and semester, and view their grades and GPA. It also includes a feature to download a PDF report of the results.

## ✨ Features

- **Intuitive Interface:** A clean and straightforward form for querying student results.
- **Detailed Grade View:** Displays a comprehensive table of subjects, grades, and credits for the selected semester or all semesters.
- **GPA Calculation:** Automatically calculates and displays the Grade Point Average (GPA).
- **PDF Report Generation:** Users can download a full academic report in PDF format. The report includes:
    - Student's name, ID, and major.
    - The official university logo.
    - A QR code linking to the student's online record.
    - A detailed table of grades.
- **Responsive Design:** The interface is optimized for viewing on both desktop and mobile devices.
- **Client-Side Operation:** The entire system runs in the browser using HTML, CSS, and JavaScript. No backend is required.

## 🚀 How to Use

1.  **Open `index.html`** in your web browser.
2.  **Enter your Student ID**.
3.  **Select your Major** from the dropdown (CS or IT).
4.  **Select the Semester** you wish to view, or choose "All Semesters" for a complete report.
5.  Click **"Show Information"**.
6.  You will be redirected to the details page with your results.
7.  On the details page, you can click **"Download Full Report"** to save a PDF copy.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- [jsPDF](https://github.com/parallax/jsPDF) - A library to generate PDFs in JavaScript.
- [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) - A jsPDF plugin for creating tables.
- [QRious](https://github.com/neocotic/qrious) - A library for generating QR codes.