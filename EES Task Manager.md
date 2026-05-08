# EES Task Manager

This is a simple, single-page web application designed to help engineering teams manage their tasks and projects efficiently. It is now called EES Task Manager. It uses a Google Sheet as its backend for data storage, allowing for easy collaboration and accessibility within a Google Drive environment.

## Features

*   **EES Task Management**: Add, edit, delete, and mark tasks as done.
*   **Dashboard**: Get a quick overview of total tasks, tasks by status, priority, and assignee, as well as overdue tasks and those due this week.
*   **All Tasks View**: A comprehensive list of all tasks with search, filter, and sort functionalities.
*   **My Tasks View**: Filter tasks by the assigned person.
*   **Calendar View**: Visualize tasks on a calendar.
*   **Progress Tracking**: Track task progress with a slider and percentage display.
*   **Priority and Status Badges**: Clearly indicate task priority and current status.
*   **Mobile Responsive**: Works well on both desktop and mobile devices.
*   **PWA Support**: Installable as a Progressive Web App on your phone or desktop.
*   **Google Sheets Backend**: All data is stored securely in your Google Drive via a Google Sheet, enabling easy sharing and team collaboration.

## Technologies Used

*   **Frontend**: HTML, CSS (Tailwind CSS), JavaScript
*   **Backend**: Google Apps Script
*   **Data Storage**: Google Sheets

## Setup and Deployment

To get started with this EES Task Manager application, please follow the detailed instructions in `SETUP_GUIDE.md`.

## Usage

1.  **Access the Web App**: Once deployed, open the provided URL in your web browser.
2.  **Add a New Task**: Click the "Add Task" button to open the form. Fill in the details and save.
3.  **View Tasks**: Navigate through the "Dashboard", "All Tasks", "My Tasks", and "Calendar" tabs to view and manage your tasks.
4.  **Edit/Delete Tasks**: Use the "Edit" and "Delete" buttons on each task card/row to modify or remove tasks.
5.  **Filter and Search**: Use the search bar and filter options in the "All Tasks" tab to quickly find specific tasks.
6.  **Refresh Data**: The data automatically refreshes every 60 seconds, or you can click the "Refresh" button for an immediate update.

## Team Members

This application is designed for use by the following team members:

*   Khairul
*   Fauzi
*   TM Soo
*   Azman
*   CS Lai
*   Ashraf
*   Rahmat
*   Ahmad

## Contributing

Feel free to modify and extend this application to suit your team's specific needs. Refer to the `Code.gs` and `index.html` files for the backend and frontend logic, respectively.
