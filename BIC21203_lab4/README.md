# BIC21203 – Lab 4a: Client-Side Scripting (JavaScript)

**Name:** NURUL LIYANA BINTI AWANG
**Student ID:** AI240083
**Course:** BIC21203

## Overview
This repository contains three JavaScript exercises demonstrating DOM selection,
event handling, input validation, loops and dynamic element creation.

## Files
- `question1/` – Interactive Text Changer (button changes paragraph text)
- `question2/` – Smart Number Validator (compares input against 10)
- `question3/` – Dynamic Number Generator (for loop builds list of 1–5)

## How to Run
1. Clone or download this repository.
2. Open the `index.html` inside each folder in a modern browser
   (Chrome / Edge / Firefox).
3. Interact with the button on each page.
   (No server or external libraries required.)

## Test Evidence
Screenshots for each question are included below:

### Q1 – Before click
![Q1 before](screenshot\question1\before\Screenshot 2026-10-21 000237.png)

### Q1 – After click
![Q1 after](screenshot\question1\after\Screenshot 2026-10-21 000242.png)

### Q2 – Test cases
![Q2](screenshot\question2\tests\Screenshot 2026-10-21 000036.png)
    (screenshot\question2\tests\Screenshot 2026-10-21 000047.png)
    (screenshot\question2\tests\Screenshot 2026-10-21 000058.png)
    (screenshot\question2\tests\Screenshot 2026-10-21 000107.png)
    (screenshot\question2\tests\Screenshot 2026-10-21 000119.png)
    (screenshot\question2\tests\Screenshot 2026-10-20 132425.png)

### Q3 – Generated list
![Q3] (screenshot\question3\Screenshot 2026-10-21 000751.png)

## Reflection
(In this lab, I learned how to separate my JavaScript from my HTML and use addEventListener to handle user interactions cleanly, rather than relying on inline onclick attributes. I also discovered that using textContent is much safer than innerHTML because it treats input as plain text, which prevents potential cross-site scripting (XSS) attacks when displaying user-facing data. For the dynamic generator in Question 3, I learned how combining a for loop with document.createElement() and appendChild() gives precise control over the DOM. By clearing the list's textContent before the loop runs, I ensured that repeated button clicks successfully prevent duplicate output.)