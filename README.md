# Markdown Viewer

This project provides a simple, single-file web application to render Markdown files (`.md`) directly in your browser. It leverages **Tailwind CSS** for a clean, responsive design and the **Marked.js** library for fast and accurate Markdown-to-HTML conversion.

## Features

*   **Markdown to HTML Conversion:** Automatically fetches `input.md` and renders its content as beautiful HTML.
*   **Responsive Design:** Built with Tailwind CSS, ensuring a great viewing experience on all devices, from desktops to mobile phones.
*   **Single-File Application:** All necessary HTML, CSS (via Tailwind CDN), and JavaScript (via Marked.js CDN) are self-contained in `index.html` for easy deployment.
*   **Easy to Use:** Just place your `input.md` file in the same directory as `index.html` and open `index.html` in your browser.

No server or build process is required for basic usage, making it ideal for quick documentation viewing or static site generation.

## Installation & Setup

1.  **Save the files:** Download `index.html` and place it in your desired project directory.
2.  **Provide Markdown:** Ensure your Markdown content is saved as `input.md` in the *same directory* as `index.html`.
3.  **Open in Browser:** Simply open the `index.html` file in any modern web browser.

## Usage

Once `index.html` is opened, it will automatically attempt to fetch and display the content of `input.md`. Any changes to `input.md` will require refreshing the `index.html` page in your browser.

## Technologies Used

*   [**Tailwind CSS**](https://tailwindcss.com/) - A utility-first CSS framework for rapidly building custom designs.
*   [**Marked.js**](https://marked.js.org/) - A full-featured markdown parser and compiler, written in JavaScript.

## License

This project is open-source and licensed under the MIT License. See the `LICENSE` file for more details.