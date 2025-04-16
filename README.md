# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
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


/* General body styling */
body {
    font-family: 'Roboto', sans-serif;
    background-color: #f5f5f5;
    color: #333;
    margin: 0;
    padding: 20px;
    line-height: 1.6;
}

/* Class selector for container */
.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    border: 2px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* ID selector for header */
#header {
    text-align: center;
    color: #2c3e50;
    margin-bottom: 30px;
    padding-bottom: 10px;
    border-bottom: 3px solid #3498db;
}

/* Class selector for styled images */
.featured-image {
    display: block;
    max-width: 100%;
    height: auto;
    margin: 20px auto;
    padding: 10px;
    border: 5px solid #3498db;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

/* Class selector for content paragraphs */
.content {
    font-size: 1.1em;
    margin: 15px 0;
    padding: 10px;
    border-left: 4px solid #e74c3c;
}

/* Hover effect for images */
.featured-image:hover {
    transform: scale(1.05);
    transition: transform 0.3s ease;
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">
        <h1 id="header">Welcome to My Styled Page</h1>
        <img src="https://via.placeholder.com/600x300" alt="Sample Image" class="featured-image">
        <p class="content">This is a sample paragraph styled with CSS. It uses a custom font, colors, and borders to enhance readability and aesthetics.</p>
        <p class="content">Another paragraph to demonstrate consistent styling across elements. The design is clean and modern, with attention to spacing and typography.</p>
    </div>
</body>
</html>
