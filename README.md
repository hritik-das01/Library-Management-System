# Library-Management-System
A sophisticated, single-page web application designed for seamless library resource management. This project features the allowance of a customer with Library ID to issue and return the book as per the mentioned date during issuing of the book. The technology uses HTML, CSS and JAVASCRIPT, system supports an integrated Library Assistant Chatbot.

Key Features :
User Authentication: Full Register/Login system with local session persistence.
Dynamic Catalog: A searchable database of over 25+ books with real-time filtering by title or author.
Loan Management: Users can issue books with custom return dates and manage active loans directly from their dashboard.
Smart Library Assistant: An integrated chatbot to help users find books, check library hours, and inquire about fine policies.
Availability Tracking: Automatic status updates (Available vs. Issued Out) based on current loan data.
Responsive Design: Optimized for both desktop and mobile viewing using a modern dark-mode aesthetic.

Tech Stack
Frontend: HTML5, CSS3 (Flexbox/Grid), Google Fonts (Inter).
Scripting: Vanilla JavaScript (ES6+).
Storage: localStorage API for persistent data handling (no database setup required).
UI Style: Glassmorphism with CSS variables for easy theme customization.

Usage:
Register a new account.
Log in to access the catalog.
Use the search bar to find specific titles.
Click "Issue Now" to add a book to your active loans.

Preview
The system uses a sleek dark interface with high-contrast red accents (--primary: #ff4d4d).
Dashboard: Displays a grid of books with unique covers generated via the Picsum API.
Chatbot: Located at the bottom right, providing instant support for library FAQs.
