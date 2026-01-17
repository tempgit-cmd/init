#### 404 Error Page - Custom Design ####


This project is a simple 404 Error page design with an interactive button to simulate fixing the error. The page displays a "404 Page Not Found" message with a "Click to Fix" button that, when clicked, shows a "Voilà! Fixed." message with a shake animation.
Features


Responsive Design: The page adjusts to different screen sizes using flexbox for centering the content vertically and horizontally.


Error Message: Displays a large, red "404" and a smaller descriptive message indicating the page does not exist.


Interactive Button: A button that simulates fixing the error with a message that appears once clicked.


Animations: Includes a shake animation for the "Fixed" message.


--------


####  Technologies Used ####


HTML: The page structure and content.


CSS: Styling of the page elements including layout, fonts, colors, and animation.


JavaScript: A simple function to display the "fixed" message when the button is clicked.


-----------


##### Files #####


index.html: The main HTML file containing the structure, styles, and interactivity.


--------

###### How to Use ######


Clone or Download the repository.


Open the index.html file in a web browser.


You will see the 404 error page with a message and a button.


Click on the "Click to Fix" button to see the interactive behavior.


Example Usage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>404 Error - Page Not Found</title>
    <style>
        /* Styles are here */
    </style>
</head>
<body>
    <h1>404</h1>
    <p>Oops! This page does not exist.</p>
    <button class="btn" onclick="fixError()">Click to Fix</button>
    <p class="message" id="fixedMessage">Voilà! Fixed.</p>

    <script>
        function fixError() {
            const message = document.getElementById("fixedMessage");
            message.style.display = "block";
            message.classList.add("animation");
        }
    </script>
</body>
</html>


------------


#### Customization #####


Button Text: You can change the button text by modifying the <button> element's text, such as:
<button class="btn" onclick="fixError()">Try Again</button>



Colors: Adjust the background and text colors in the CSS styles to fit your website's theme:
body {
    background-color: #f4f4f9; /* Change background color */
    color: #333; /* Change text color */
}
.btn {
    background-color: #4CAF50; /* Button background color */
}



Animation: You can modify the shake animation in the CSS for a different effect. Adjust the @keyframes shake rule to change the movement.



--------


##### License #######


This project is licensed under the MIT License - see the LICENSE file for details.


-------


Let me know if you need further details or additional sections!
