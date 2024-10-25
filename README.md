# CS 140: In Class Assignment: Basic Button

## Instructions

You have been given some starter code:

- Blank HTML page
- JavaScript file with a function called myAlert

1. Add a button on the HTML page (index.html)
1. Write some JavaScript code (script.js) inside the function (between the curly braces) that creates an alert
1. Set up the button in the HTML page to run the alert code inside the function.
1. Submit assignment repo link on Brightspace.

## What's Inside?

| File Type | Description                                      | How to Use                                 |
|-----------|--------------------------------------------------|--------------------------------------------|
| `.html`   | HTML files define the structure of your web pages. | Add your content and structure here.      |
| `.css`    | CSS files style your web pages.                  | Use these to make your site look amazing. |
| `.js`     | JavaScript files add interactivity to your pages. | Bring your pages to life with JS.         |


## Handy Tags, CSS Rules, and JavaScript Snippets

### HTML Tags to Remember

| Tag        | Description                           | Example                                 |
|------------|---------------------------------------|-----------------------------------------|
| `<a>`      | Creates a hyperlink to another page.  | `<a href="https://example.com">Visit!</a>` |
| `<img>`    | Embeds an image in your webpage.      | `<img src="image.jpg" alt="A cool image">` |
| `<ul>`, `<li>` | Creates a list of items.             | `<ul><li>Item 1</li><li>Item 2</li></ul>`   |
| `<div>`    | Defines a division or section.        | `<div>Content here</div>`               |

### CSS Rules to Spice Up Your Site

| Rule              | Description                                | Example                               |
|-------------------|--------------------------------------------|---------------------------------------|
| `font-family`     | Changes the font of your text.             | `font-family: 'Arial', sans-serif;`   |
| `margin`, `padding` | Controls the space around and inside elements. | `margin: 10px; padding: 20px;`        |
| `border`          | Adds a border around elements.             | `border: 2px solid #000;`             |
| `background-color`| Sets the background color of elements.     | `background-color: #ffcc00;`          |

### JavaScript Snippets for Interactivity

- **Show an Alert**:
  - `alert('Welcome to CS 140 Web Development!');`
- **Change Text Content**:
  - Example: `document.getElementById('exampleId').textContent = 'Hello, CS 140!';`
- **Add a Click Event**:
  - Example:
    ```javascript
    document.getElementById('clickMeButton').addEventListener('click', function() {
        alert('You clicked the button!');
    });
    ```

*This document was initially drafted with the help of ChatGPT. It has been edited and customized to fit our class's needs.
*
