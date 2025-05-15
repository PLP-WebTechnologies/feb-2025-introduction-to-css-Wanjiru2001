/* style.css */

/* ID selector */
#main-title {
  color: darkblue;
  font-family: 'Arial', sans-serif;
  margin-bottom: 20px;
  border-bottom: 2px solid darkblue;
  padding-bottom: 5px;
}

/* Class selector */
.highlight {
  background-color: lightyellow;
  padding: 10px;
  border: 1px solid #ccc;
  margin: 15px 0;
  font-family: 'Georgia', serif;
}

/* Element selector */
p {
  color: #333;
  line-height: 1.6;
  margin: 10px 0;
}

/* Style an image */
img {
  display: block;
  max-width: 100%;
  height: auto;
  border: 5px solid #444;
  padding: 5px;
  margin: 20px 0;
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CSS Introduction</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <h1 id="main-title">Welcome to CSS Styling</h1>

  <p>This paragraph uses the default styling applied to all paragraphs.</p>

  <p class="highlight">
    This paragraph uses the <code>highlight</code> class to stand out.
  </p>

  <img src="https://via.placeholder.com/300x150" alt="Sample Image" />

  <p>Another paragraph to show consistent styling and readability.</p>

</body>
</html>
