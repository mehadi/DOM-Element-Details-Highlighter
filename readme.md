# DOM Element Details Highlighter

This repository contains code for a simple web application that highlights DOM elements on mouse hover and displays their details on click. It's built using HTML, CSS, JavaScript, and jQuery.

## Features

- **Element Highlighting**: Hovering over an element highlights it.
- **Element Details**: Clicking on an element displays its details, including tag name, id, classes, and text content.
- **Recursive Traversal**: The script recursively traverses through nested elements to retrieve details.
- **Smooth Transitions**: Smooth transition effects for highlighting and unhighlighting elements.

## Usage

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Hover over elements to see them highlighted.
4. Click on any element to view its details in the console.

## Dependencies

- [jQuery](https://jquery.com/): JavaScript library used for DOM manipulation and event handling.

## How it Works

The JavaScript script attached to the HTML page listens for mouse events such as hover and click. It utilizes jQuery to handle these events and manipulate the DOM.

When hovering over an element, it adds a CSS class to highlight it. Clicking on an element triggers a function that extracts its details by recursively traversing through its children elements.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
