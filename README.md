# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

**Create a style.css file.**

}Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

**ANSWERS**/* Global Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Header Styling using ID */
#main-header {
    background-color: #007BFF;
    color: white;
    text-align: center;
    padding: 20px;
    border-bottom: 4px solid #0056b3;
}

/* Styling Section using Class */
.content {
    text-align: center;
    padding: 20px;
    margin: 20px auto;
    width: 80%;
    background-color: white;
    border: 2px solid #ddd;
    border-radius: 10px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

/* Styling Paragraph */
.description {
    font-size: 18px;
    font-style: italic;
    margin-bottom: 20px;
}

/* Styling an Image */
.styled-image {
    display: block;
    margin: 20px auto;
    border: 5px solid #007BFF;
    border-radius: 10px;
    padding: 10px;
    width: 300px;
}

/* Footer Styling using ID */
#footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
    border-top: 4px solid #555;
}

**APPLYING CSS TO HTML**
<!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <h1 class="title">Hello World! </h1>
      <p id="currentTime"></p>
      <script src="script.js"></script>
  </body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking the CSS file -->
</head>
<body>
  

    <!-- Header Section -->
    <header id="main-header">
        <h1>ROTICH'S STORE</h1>
    </header>

    <!-- Main Content -->
    <main>
        <section class="content">
            <h2>About Me</h2>
            <p class="description">Hello esteemed customers we really appreciate your full support. Thanks</p>
        </section>

        <!-- Styled Image -->
        <section class="image-section">
            <img src="https://assets.onecompiler.app/43dbxytfk/43dbxnqfx/WIN_20241018_05_58_58_Pro.jpg" alt="Sample Image" class="styled-image">
        </section>
    </main>

    <!-- Footer Section -->
    <footer id="footer">
        <p>Contact: rotichelkana3@gmail.com</p>
    </footer>

</body>
</html>

