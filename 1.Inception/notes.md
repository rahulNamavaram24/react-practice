
# Web Development Concepts

## What is Emmet?
Emmet is a plugin for many popular text editors which greatly improves HTML & CSS workflow. It allows developers to write HTML and CSS code with shortcuts that expand into full-fledged code snippets, making the coding process faster and more efficient.

## Difference between a Library and Framework?
- **Library**: A collection of pre-written code that users can call upon to solve common tasks. The control remains with the developer who decides when and where to call the library.
- **Framework**: A structure where the framework itself calls the developer’s code as needed. It provides a foundation with a particular style and design pattern, enforcing a certain way of developing applications.

## What is CDN? Why do we use it?
- **CDN (Content Delivery Network)**: A distributed network of servers that deliver web content based on the geographic locations of users.
- **Why use it?**: CDNs enhance the performance of web applications by reducing load times, increasing content availability and redundancy, and improving security.

## Why is React known as React?
React is named "React" because it enables developers to build interactive user interfaces that react to data changes efficiently. The core concept is that the UI should react to changes in data, automatically updating and rendering components as needed.

## What is crossorigin in script tag?
The `crossorigin` attribute in a `<script>` tag is used to handle CORS (Cross-Origin Resource Sharing) requests. It defines how the browser should handle cross-origin requests for the script:
- **`anonymous`**: Requests are made without including user credentials.
- **`use-credentials`**: Requests are made including user credentials (cookies, HTTP authentication, and client-side SSL certificates).

## What is the difference between React and ReactDOM?
- **React**: The core library for building UI components. It focuses on the creation of components, their lifecycle, and the logic behind them.
- **ReactDOM**: A library that provides DOM-specific methods to manage and update the DOM, rendering React components into the DOM.

## What is the difference between react.development.js and react.production.js files via CDN?
- **react.development.js**: This file is unminified and includes additional warnings and error messages to help developers debug their applications. It is meant for use during development.
- **react.production.js**: This file is minified and optimized for performance. It removes all warnings and error messages, making it suitable for production use.

## What is async and defer?
- **async**: The `async` attribute for a script tag loads the script asynchronously. Once the script is downloaded, it executes immediately, potentially before the page has fully loaded.
- **defer**: The `defer` attribute loads the script in parallel with other resources, but ensures that the script will execute only after the page has fully loaded. This attribute maintains the order of scripts as they appear in the document.
