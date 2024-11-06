# Simple Webpage

This is a basic HTML and CSS project that demonstrates how to create a simple webpage with a welcoming message, a clickable button, and a footer.

## Project Structure

- **index.html**: The main HTML file that structures the webpage.
- **style.css**: (Optional) A separate CSS file that contains styles to enhance the appearance of the webpage.
  
## Features

1. **Welcome Heading**: The main heading welcomes users to the webpage.
2. **Description Paragraph**: A brief paragraph explaining the purpose of the webpage.
3. **Interactive Button**: A button that displays a JavaScript alert message when clicked.
4. **Footer**: Contains a copyright notice.

## HTML File (index.html)

The `index.html` file includes the basic structure:
- `<!DOCTYPE html>` specifies HTML5.
- `<h1>` element for the main heading.
- `<p>` element for a description of the page.
- A clickable button with an `onclick` event that triggers a welcome alert.
- A footer with copyright information.

## CSS (style.css)

The CSS styles the HTML to make it visually appealing. Key styles include:
- Centering content and setting a background color for the page.
- Adding padding, colors, and hover effects to the button.
- Styling text for readability and a clean look.

### Example

Below is a sample of what the HTML and CSS look like:

```html
<h1>Welcome to My Simple Webpage</h1>
<p>This is a basic webpage created with HTML.</p>
<button onclick="alert('Hello, welcome to my webpage!')">Click Me</button>
<footer>&copy; 2024 Simple Webpage. All rights reserved.</footer>
