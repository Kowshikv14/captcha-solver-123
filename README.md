# Captcha Solver Interface
A simple, responsive web application built with HTML, Tailwind CSS, and vanilla JavaScript to demonstrate a client-side interface for solving captchas. While this application provides the UI for input and display, the actual "solving" or verification logic for arbitrary captchas would typically reside on a backend server. For the included `sample.png` captcha, a client-side verification is implemented.

## Features
*   **Responsive Design:** Optimized for various screen sizes using Tailwind CSS.
*   **Dynamic Image Loading:** Displays a captcha image. Defaults to `sample.png` but can load images from a specified URL via a query parameter.
*   **User Input Field:** Allows users to type their perceived captcha solution.
*   **Client-Side Validation (for `sample.png`):** Provides immediate feedback for the hardcoded sample captcha.
*   **Simple UI:** Clean and intuitive interface for interaction.

## Usage
To use this application:
1.  Save the `index.html`, `README.md`, `LICENSE`, and `sample.png` files into the same directory.
2.  Open `index.html` in your web browser.

### Loading Custom Captcha Images
You can load a captcha image from an external URL by appending a `?url=` query parameter to the `index.html` URL.

**Example:**
If your `index.html` is hosted at `http://localhost:8000/index.html`, you can load an image like this:
`http://localhost:8000/index.html?url=https://example.com/some-captcha-image.png`

Please note that for external URLs, the application only provides the input interface. Actual verification would require a server-side component.

## Technologies Used
*   **HTML5:** For the page structure.
*   **Tailwind CSS:** For styling and responsive design.
*   **JavaScript (Vanilla):** For dynamic behavior and URL parameter handling.

## License
This project is open-sourced under the MIT License. See the `LICENSE` file for more details.