# GitHub User Lookup Application

This is a simple, single-page web application that allows users to look up GitHub profiles by username. It fetches public profile data from the GitHub API and displays it in a clean, responsive interface powered by Tailwind CSS.

## Features

*   **GitHub User Search**: Enter a GitHub username to retrieve and display their public profile information.
*   **Responsive Design**: The interface is fully responsive, adapting to various screen sizes using Tailwind CSS.
*   **Account Age Display**: In addition to the creation date, the application calculates and displays the approximate age of the GitHub account in years.
*   **ARIA Live Alerts**: Provides accessibility improvements by announcing lookup progress and status updates to screen readers using an `aria-live` region.
*   **Local Storage Caching**: The last successfully looked-up user's data is cached in the browser's `localStorage`. This data is automatically restored and displayed upon subsequent visits to the page, providing a faster and more consistent user experience.
*   **Error Handling**: Gracefully handles cases where a username is not found or other API errors occur.

## How to Use

1.  **Open `index.html`**: Simply open the `index.html` file in your web browser.
2.  **Enter Username**: Type a GitHub username into the input field.
3.  **Click Lookup**: Click the "Lookup" button (or press Enter) to fetch and display the user's data.
4.  **Cached Data**: If you previously looked up a user, their data will automatically appear on page load.

## Technologies Used

*   **HTML5**: For the structure of the web page.
*   **Tailwind CSS**: For utility-first styling, ensuring a modern and responsive design.
*   **JavaScript (ES6+)**: For fetching data from the GitHub API, DOM manipulation, and implementing features like account age calculation and local storage caching.
*   **GitHub API**: To retrieve public user profile data.

## Project Structure

This project consists of a single `index.html` file, containing all HTML, CSS (via Tailwind CDN), and JavaScript.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for full details.
