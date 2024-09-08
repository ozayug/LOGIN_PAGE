# LOGIN_PAGE

HTML and CSS Overview:-

1.HTML (HyperText Markup Language): Used to create the structure and content of the web page.
2.CSS (Cascading Style Sheets): Used to style the HTML content, including the layout, colors, fonts, and positioning of elements.

1.HTML Explanation:-

1.DOCTYPE Declaration and Head Section:

<!DOCTYPE html>: Declares the document type as HTML5.
<html lang="en">: Begins the HTML document with English as the language.
<meta charset="UTF-8">: Sets the character encoding to UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Ensures the page is responsive on all devices.
<title>Student Login Page</title>: Sets the title of the page shown in the browser tab.
<link rel="stylesheet" href="styles.css">: Links the HTML page to an external CSS file (styles.css) for styling.

2.Body Section:

<div class="login-container">: Creates a container for the login form.
<h2>Student Login</h2>: Displays the heading of the form.
<form action="#" method="post">: Begins the form, using the post method to send data (the # indicates the action is not linked to a server in this example).
<label> and <input>: Create labeled fields for "Username" and "Password".
<button type="submit">: Creates a button to submit the form.

3.CSS Explanation:-

* { margin: 0; padding: 0; }: Resets default margin and padding for all elements.
body {}: Styles the body with a background color, sets the font, and centers content using Flexbox.
.login-container {}: Styles the login form container with padding, a background color, rounded corners, and a shadow.
h2, input, button {}: Styles the form elements (heading, inputs, and button) with specific colors, padding, and effects.

4.How to Run This Code:
Create Files:

Create a folder on your computer (e.g., StudentLogin).
Inside the folder, create two files: index.html and styles.css.
Copy the Code:

Copy the provided HTML code into index.html.
Copy the CSS code into styles.css.
Open in a Browser:

Open index.html in any web browser (e.g., Chrome, Firefox).
You can simply double-click on the index.html file or right-click and select "Open with" and choose your browser.

5.Additional Details:
Languages Used:
HTML: Defines the structure and content of the page.
CSS: Adds styling, layout, and visual effects to the HTML content.
How to Make it Functional:
Currently, this code only creates a front-end login form. To make it functional, you would need to use a backend language (like Python, PHP, or JavaScript with Node.js) and a database (like MySQL) to handle user authentication.

6.Next Steps:
If you want to make this login page interactive (e.g., validating user input), you could use JavaScript to add such functionalities.