# To Do List App

This project is a simple To Do List web application that allows users to add, delete, and reorder tasks. Users can also mark tasks as completed by double-clicking on them.

## Features

- Add new tasks to the list
- Mark tasks as completed by double-clicking
- Delete tasks by clicking the "X" button
- Reorder tasks using drag-and-drop functionality

## Technologies Used

- HTML
- CSS
- JavaScript
- jQuery
- jQuery UI

## Getting Started

### Prerequisites

To run this project locally, you need a web browser and a local server. You can use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VSCode or any other method to serve HTML files.

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/todo-list-app.git
   ```

Navigate to the project directory:

cd todo-list-app

Open index.html in your browser or use a local server to serve the file.

Usage
Enter a task in the input field and click the "Add" button to add it to the list.
Double-click on a task to mark it as completed.
Click the "X" button next to a task to delete it.
Drag and drop tasks to reorder them.

File Structure

todo-list-app/
├── dist/
│ ├── scripts.dist.js
│ └── styles.dist.css
├── js/
│ ├── fetch-polyfill.js
│ └── promise-polyfill.js
├── index.html
├── README.md
└── src/
├── scripts.js
└── styles.css

Customization

CSS: Customize the styling in src/styles.css.
JavaScript: Add or modify functionality in src/scripts.js.
Minified Files

The project includes minified versions of CSS and JS files located in the dist directory. These files are referenced in index.html.

Dependencies

This project uses the following dependencies:

jQuery 3.5.1
jQuery UI 1.12.1
Acknowledgements

This project was inspired by various To Do List applications.

License

This project is licensed under the MIT License.
