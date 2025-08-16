# My Offline Library
This is a single-page web application that functions as a personal, offline-first library. It allows you to manage and read your book collection directly in the browser without needing an internet connection.

## Features
* **Add Books**: Easily upload book files (e.g., .txt, .pdf) with their title, author, and a custom group name.
* **Organize into Groups**: Group your books into categories like "Fiction," "Reference," or "School Books" for better organization.
* **Read & View**: Read .txt files directly within the app's built-in viewer. For other file types like .pdf, the app provides a download link.
* **Manage Books**: Edit the details of any book or remove it from your collection with a simple click.
* **Search**: Find books quickly by searching for their title, author, or group name.
* **Offline Access**: Your entire library is stored locally on your device using IndexedDB, so it's always available, even when you're not online.

## How to Use
* **Open the App**: Open the index.html file in a modern web browser.
* **Add a Book**: Click the "Add New Book" button. Fill in the book's details, including a custom group name if you like, and upload the file.
* **Browse Your Library**: The main page displays your books organized by their assigned groups. You can click on a book to read, edit, or remove it.
* **Find a Book**: Use the search bar to filter your library by title, author, or group.

## Technology Stack
* **HTML5**: Provides the structure for the application.
* **Tailwind CSS**: Used for all styling, ensuring a clean and responsive design.
* **JavaScript**: Powers the application's logic, including all user interactions and data management.
* **IndexedDB**: The core technology for persistent, local storage, which makes the app function completely offline.

## Prototype
[My Offline Library](https://my-islamic-library.netlify.app/)
