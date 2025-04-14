# stylishpage

<!DOCTYPE html>
Declares that this is an HTML5 document.

html
Copy
Edit
<html lang="en">
Starts the HTML document and sets the language to English.

html
Copy
Edit
<head>
Begins the <head> section, which includes meta info, title, and styles.

html
Copy
Edit
    <meta charset="UTF-8">
Sets character encoding to UTF-8, allowing for special characters and emojis.

html
Copy
Edit
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
Makes the page responsive on mobile devices by controlling the layout width and scale.

html
Copy
Edit
    <title>Styled Webpage</title>
Sets the title of the webpage (shows in the browser tab).

html
Copy
Edit
    <style>
Starts an internal CSS style block.

css
Copy
Edit
        body {
            background: url('https://source.unsplash.com/random/1600x900') no-repeat center center/cover;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
Styles the whole page (<body>):

background: uses a random image from Unsplash as the background, centered and covering the whole screen.

color: white: sets the default text color to white.

font-family: uses Arial, falling back to sans-serif if not available.

text-align: center: centers text horizontally.

margin and padding: removes default spacing around the page.

css
Copy
Edit
        .container {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            margin: 50px auto;
            width: 60%;
            border-radius: 10px;
        }
Styles the div with class container:

background: rgba(0,0,0,0.6): a semi-transparent black background for readability over the image.

padding: 20px: adds space inside the container.

margin: 50px auto: adds top & bottom margin, and horizontally centers the container.

width: 60%: container takes 60% of page width.

border-radius: 10px: gives rounded corners.

css
Copy
Edit
        h1 {
            color: #ffcc00;
        }
Styles the heading:

color: #ffcc00: golden yellow text color.

css
Copy
Edit
        p {
            line-height: 1.6;
            font-size: 18px;
        }
Styles the paragraph:

line-height: 1.6: adds vertical spacing between lines.

font-size: 18px: makes text easier to read.

html
Copy
Edit
    </style>
</head>
Ends the style section and the <head>.

html
Copy
Edit
<body>
Starts the visible page content.

html
Copy
Edit
    <div class="container">
Creates a centered, styled content box with the .container class.

html
Copy
Edit
        <h1>Welcome to My Stylish Page</h1>
Adds a large heading inside the container.

html
Copy
Edit
        <p>
            This webpage uses a background image, a semi-transparent overlay for readability,
            and custom text styles for better presentation. The colors and font sizes enhance
            readability and aesthetics.
        </p>
Adds a paragraph explaining the design choices.

html
Copy
Edit
    </div>
</body>
</html>
Closes the container, the body, and the HTML document.
