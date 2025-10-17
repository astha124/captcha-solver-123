# CAPTCHA Solver Demo Application

This is a simple single-page responsive web application built with HTML, Tailwind CSS, and JavaScript. It serves as a basic demonstration for displaying and interacting with a CAPTCHA image, either from a dynamically provided URL or a local default image.

## Features
- **Responsive Design:** Utilizes Tailwind CSS for a modern, mobile-first, and responsive user interface.
- **Dynamic Image Loading:** The CAPTCHA image source can be set via a URL query parameter.
- **Default Image Fallback:** If no URL parameter is provided, a local `sample.png` image is displayed by default.
- **Simple CAPTCHA Input:** Provides an input field for users to type the CAPTCHA characters.
- **Basic Solver Logic:** On submission, the entered text is displayed, simulating a 'solver' output.

## Usage
To use this application, simply open the `index.html` file in your web browser.

### Loading a Custom CAPTCHA Image
You can specify a custom CAPTCHA image by appending a `?url=` query parameter to the URL in your browser's address bar.

For example:
```plaintext
index.html?url=https://example.com/path/to/your/captcha.png
```

If no `url` parameter is provided, the application will default to displaying the `sample.png` image located in the same directory.

### Entering and Solving the CAPTCHA
1.  Observe the CAPTCHA image displayed.
2.  Type the characters you see in the image into the input field labeled "Enter CAPTCHA".
3.  Click the "Solve CAPTCHA" button.
4.  The text you entered will be displayed below the button.

## Technologies
- HTML5
- Tailwind CSS (via CDN)
- JavaScript

## License
This project is open-sourced under the MIT License. See the `LICENSE` file for more details.