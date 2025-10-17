# Markdown Viewer Application

This project provides a simple, single-file web application that renders a Markdown file (`input.md`) into HTML using the `marked` JavaScript library and styles it with Tailwind CSS.

## Features

*   **Markdown to HTML Conversion:** Converts `input.md` content into formatted HTML.
*   **Responsive Design:** Utilizes Tailwind CSS for a clean, responsive layout.
*   **Client-Side Rendering:** All processing happens in the browser.

## Getting Started

### Prerequisites

To run this application, you only need a modern web browser.

### Installation

1.  Save the `index.html` file to your local machine.
2.  Place your Markdown content in a file named `input.md` in the **same directory** as `index.html`.

### Usage

1.  Open `index.html` in your web browser.
2.  The content of `input.md` will be automatically fetched and rendered as HTML on the page.

## Project Structure

*   `index.html`: The main HTML file containing the web application, including embedded JavaScript and CSS (via CDN).
*   `input.md`: The Markdown file that will be converted and displayed.

## Dependencies

*   [Tailwind CSS](https://tailwindcss.com/): Used for styling the HTML page (via CDN).
*   [Marked.js](https://marked.js.org/): A Markdown parser and compiler. Built for speed (via CDN).

## Contributing

Feel free to fork this project, open issues, or submit pull requests. Any contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.