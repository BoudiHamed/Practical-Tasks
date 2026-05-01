# Practical Tasks - Vanilla JS To-Do App

This is a functional to-do application built to practice DOM manipulation and state management using Vanilla JavaScript and Tailwind CSS[cite: 1]. The goal was to create a tool that handles data persistence and a dynamic UI without using external frameworks[cite: 1].

 Main Features

*   Task Persistence: All tasks are saved to localStorage, so they don't disappear when you refresh the page[cite: 1].
*   CRUD Operations: You can create new tasks, read them from the list, update their status to completed, and delete them[cite: 1].
*   Event Handling: Users can add tasks by clicking the button or pressing the Enter key[cite: 1].
*   Confirmation Modal: A custom modal pops up to confirm before deleting all tasks to prevent accidental data loss[cite: 1].

 Technical Overview

 State Management
Instead of just grabbing text from the screen, I used a central array called dataOfTasksArray to store objects for each task[cite: 1]. Every time a user adds or deletes a task, the array is updated first, and then the UI and localStorage are synced[cite: 1]. This makes the data more reliable.

 Event Delegation
I implemented event delegation by adding a single click listener to the document[cite: 1]. This allows the app to handle clicks on delete buttons even if those buttons were created after the page initially loaded

 Logic Flow
1. User inputs data and triggers the checkBoxAppearance function
2. A unique ID is generated using Date.now() to identify the task
3. The UI is updated using insertAdjacentHTML for performance
4. The task is saved as a JSON string in localStorag

Tools Used

*   HTML5 and CSS3[cite: 1]
*   Tailwind CSS for layout and styling
*   Vanilla JavaScript (ES6)
*   LocalStorage API

 How to Run

1. Clone this repository[cite: 1].
2. Open index.html in any modern browser
3. No build steps or installations needed

 Contact

Abdelrahman Hamed
Junior Full-Stack Developer
