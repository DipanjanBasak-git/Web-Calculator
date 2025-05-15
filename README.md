# 🧮 Calculator Project
## 📋 Overview
This is a web-based calculator built as part of my internship at Micro IT India. The calculator performs basic arithmetic operations with a clean, nature-inspired design, featuring a semi-transparent overlay for readability and a modern user interface. This project demonstrates my skills in frontend development, focusing on DOM manipulation, event handling, responsive design, and Firebase integration for analytics tracking.
🔗 Live Demo: https://calculator-e04b2.web.app/

## 📸 Screenshots
![Screenshot 2025-05-15 085456](https://github.com/user-attachments/assets/aa638956-0355-46eb-90b5-4b5fe422f72c)

## ✨ Features

➕ Basic Arithmetic Operations: Supports addition, subtraction, multiplication, and division.
🗑️ Clear Button: Resets the calculator to start a new calculation with a single click.
🎨 Nature-Inspired Design: Features a background image from Unsplash with a semi-transparent overlay for enhanced readability.
🌟 Interactive UI: Buttons with hover and active effects, color-coded for operators, clear, and equals functions.
📱 Responsive Design: Adapts seamlessly to different screen sizes, ensuring usability on both desktop and mobile devices.
🖼️ Fade-In Animation: Calculator container fades in on page load for a polished user experience.
📊 Firebase Analytics: Tracks user interactions using Firebase Analytics for insights into usage patterns.

## 🛠️ Tech Stack

Frontend: HTML, CSS, Vanilla JavaScript
Hosting: Firebase Hosting
Analytics: Firebase Analytics (via Firebase SDK v11.7.3)
Background Image: Sourced from Unsplash
Icons: None (pure CSS styling for buttons)

## ⚙️ Setup Instructions
To run this calculator locally, follow these steps:

Clone the Repository:git clone https://github.com/DipanjanBasak-git/calculator.git


Navigate to the Project Directory:cd calculator


Open the Project:
Open public/index.html in a web browser to use the calculator locally.
Alternatively, use a local server (e.g., Live Server in VS Code) for a better development experience.



🔥 Host on Firebase
This project is hosted on Firebase Hosting. To host your own copy:

Install Firebase CLI:npm install -g firebase-tools


Log in to Firebase:firebase login


Initialize Firebase:
Run firebase init in your project directory.
Select Hosting, choose your Firebase project, and set the public directory to public.
Ensure your index.html is in the public folder.


Deploy to Firebase:firebase deploy


Your site will be live at the URL provided (e.g., https://<your-project-id>.web.app/).



## 📂 Project Structure

public/index.html: Main HTML file containing the calculator structure, styles, scripts, and Firebase integration.
README.md: Project documentation (this file).

## 🖱️ Usage

Click the number buttons (0-9) to input digits.
Use the decimal button (.) to add a decimal point.
Click the operation buttons (+, -, *, /) to perform calculations.
Press the = button to compute and display the result.
Click the C button to clear the display and start a new calculation.
If an error occurs (e.g., invalid expression), the display shows "Error" and auto-clears after 1 second.

## 🙏 Credits

Internship: This project was developed during my internship at Micro IT India.
Background Image: Nature background sourced from Unsplash.

## 👨‍💻 About Me
I’m Dipanjan Basak, a Computer Science and Business Systems student at IEM Kolkata, passionate about Full Stack Development, AI, and Data Science. This calculator project is a part of my internship work at Micro IT India, showcasing my ability to build functional and visually appealing web applications with analytics integration. Connect with me on LinkedIn or check out my other projects on GitHub.

Feel free to star this repository if you find it useful! 🌟
