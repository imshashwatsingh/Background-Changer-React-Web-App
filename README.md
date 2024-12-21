<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Background Changer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
      padding: 20px;
    }
    h1, h2 {
      color: #2c3e50;
    }
    code {
      background-color: #eef;
      padding: 2px 4px;
      border-radius: 4px;
    }
    pre {
      background: #f4f4f4;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 5px;
      overflow-x: auto;
    }
    a {
      color: #3498db;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    ul {
      padding-left: 20px;
    }
    .image-preview {
      text-align: center;
      margin: 20px 0;
    }
    .image-preview img {
      max-width: 100%;
      height: auto;
      border: 1px solid #ddd;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <h1>Background Changer in React</h1>

  <p>A simple and visually appealing background color changer built with React and Tailwind CSS. This project demonstrates the use of React hooks and dynamic styling to create an interactive user interface.</p>

  <h2>Features</h2>
  <ul>
    <li><strong>Dynamic Backgrounds:</strong> Change the background color of the screen with a single click.</li>
    <li><strong>Responsive Design:</strong> Buttons are neatly arranged and work on different screen sizes.</li>
    <li><strong>Smooth Transitions:</strong> Includes smooth color transitions for a better user experience.</li>
    <li><strong>Reset Functionality:</strong> Reset the background to the default color (olive) with a single click.</li>
  </ul>

  <h2>Preview</h2>
  <div class="image-preview">
    <img src="https://via.placeholder.com/800x400?text=Background+Changer+Preview" alt="Background Changer Preview">
  </div>

  <h2>Technologies Used</h2>
  <ul>
    <li><strong>React:</strong> A JavaScript library for building user interfaces.</li>
    <li><strong>Tailwind CSS:</strong> A utility-first CSS framework for styling.</li>
    <li><strong>React Hooks:</strong> For state management using the <code>useState</code> hook.</li>
  </ul>

  <h2>Getting Started</h2>

  <h3>Prerequisites</h3>
  <p>Ensure you have the following installed on your system:</p>
  <ul>
    <li><a href="https://nodejs.org/">Node.js</a> (version 14 or higher)</li>
    <li><a href="https://www.npmjs.com/">npm</a> or <a href="https://yarnpkg.com/">yarn</a></li>
  </ul>

  <h3>Installation</h3>
  <pre>
1. Clone the repository:
   git clone https://github.com/imshashwatsingh/background-changer.git

2. Navigate to the project directory:
   cd background-changer

3. Install the dependencies:
   npm install
   # or
   yarn install
  </pre>

  <h3>Usage</h3>
  <pre>
1. Start the development server:
   npm run dev

2. Open your browser and visit:
   http://localhost:5173

3. Use the buttons to change the background color or reset it to the default.
  </pre>

  <h2>Project Structure</h2>

  <h2>How It Works</h2>
  <ol>
    <li><strong>State Management:</strong> The <code>useState</code> hook is used to manage the current background color.</li>
    <li><strong>Dynamic Styles:</strong> The <code>style</code> prop dynamically applies the selected color to the background.</li>
    <li><strong>Buttons:</strong> Buttons with specific colors trigger <code>setColor</code> to update the state.</li>
  </ol>

  <h2>Future Improvements</h2>
  <ul>
    <li>Add more color options.</li>
    <li>Implement a color picker for custom colors.</li>
    <li>Save the selected color in local storage to persist the user's preference.</li>
    <li>Add animations to enhance the user experience.</li>
  </ul>

  <h2>License</h2>
  <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>
</body>
</html>