Week 12 - Performance Optimization
Overview

This website demonstrates HTML, CSS, and JavaScript concepts through a peanut butter and jelly sandwich application. The project includes user interaction, state management, and external data loaded from an API. Performance improvements were added to reduce unnecessary work and make the application more efficient.

Features
Displays random cooking tips
Loads external JSON data using the Fetch API
Shows cooking community members from an API
Uses state management to track the number of sandwiches
Updates the page dynamically based on user interaction
Limits displayed API users to improve readability
Reduces unnecessary DOM updates for better performance
Files Included
index.html
home.html
about.html
styles.css
script.js
Performance Note

One inefficient part of the application was repeatedly updating the page while displaying user data from the API. The code originally updated innerHTML during every loop iteration, causing multiple DOM updates. I improved this by building all of the HTML in a single variable and updating the page one time after the loop. The application also displays only the first five users instead of all available users, reducing unnecessary content and improving clarity.

Reflection

How did thinking about efficiency change the way you approach writing your code?

Thinking about efficiency helped me focus on reducing unnecessary work instead of only making the program function correctly. I learned that updating the page fewer times and displaying only the information users need can improve performance and make the application easier to maintain. Considering efficiency early in development helps create cleaner and more organized code.

Previous Week Features
External Data

The application retrieves user information from an external API using the Fetch API and JSON data. The data is processed and displayed dynamically on the page.

State Management

The application uses JavaScript state management through a sandwich counter. Users can increase or decrease the number of sandwiches, and the displayed value updates immediately to reflect the current state.
