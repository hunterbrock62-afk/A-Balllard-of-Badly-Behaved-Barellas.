# A-Balllard-of-Badly-Behaved-Barellas.
My book.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Chapter 1 - My Book</title>
  <link rel="stylesheet" href="style.css">
  <script>
    function saveBookmark() {
      localStorage.setItem("bookmark", "chapter1.html");
      alert("Bookmark saved!");
    }
  </script>
</head>
<body>
  <h2>Chapter 1</h2>
  <p>Here’s where you put your story text for Chapter 1...</p>
  <p>More story text...</p>

  <button onclick="saveBookmark()">Save Bookmark</button> |
  <a href="chapter2.html">Next Chapter →</a> |
  <a href="index.html">Back to Contents</a>
</body>
</html>
body {
  font-family: Georgia, serif;
  line-height: 1.6;
  max-width: 700px;
  margin: 40px auto;
  padding: 0 15px;
  background: #fefefe;
  color: #222;
}

h1, h2, h3 {
  text-align: center;
}

button {
  background: #444;
  color: white;
  padding: 10px;
  border: none;
  cursor: pointer;
}

button:hover {
  background: #222;
}