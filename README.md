Event Registration System
​A lightweight, dynamic web application designed to handle online event registrations. This project replaces manual entry systems with a real-time, validated digital solution.
​Features:
​
Real-time Form Validation: Ensures user data integrity (Name and Email checks) before submission.
​Dynamic Seat Management: Automatically updates the available seat count in the UI without page refreshes.
​Interactive UI: Uses DOM manipulation to show personalized confirmation messages and error states.
​Error Handling: Gracefully handles "Sold Out" scenarios and invalid user inputs.
​
Technologies Used:
​
HTML5: Semantic structure for the registration form.
​CSS3: Responsive styling and state management (hidden/visible elements).
​JavaScript (ES6): Core logic, Event Listeners, and DOM Manipulation.

How It Works:
​Selection: The script selects DOM elements using document.getElementById.
​Listening: An addEventListener waits for the form's submit event.
​Prevention: event.preventDefault() stops the browser from refreshing, allowing for a Single Page Application (SPA) feel.
​Validation: Logic checks if inputs meet specific criteria (e.g., non-empty, valid email format).
​Execution: If valid, the seat variable is decremented, and the UI is updated to show success.
