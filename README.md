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
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Book</title>
  <link rel="stylesheet" href="style.css">
  <script>
    // Go to last bookmark
    function goToBookmark() {
      const lastChapter = localStorage.getItem("bookmark");
      if(lastChapter) {
        window.location.href = lastChapter;
      } else {
        alert("No bookmark saved yet!");
      }
    }
  </script>
</head>
<body>
  <h1>📖 My Book Title</h1>
  <h3>Table of Contents</h3>
  <ul>
    <li><a href="chapter1.html">Chapter 1</a></li>
    <li><a href="chapter2.html">Chapter 2</a></li>
    <li><a href="chapter3.html">Chapter 3</a></li>
    <li><a href="chapter4.html">Chapter 4</a></li>
    <li><a href="chapter5.html">Chapter 5</a></li>
  </ul>
  <button onclick="goToBookmark()">Go to My Bookmark</button>
</body>
</html>
/mybook
  ├── index.html
  ├── chapter1.html
  ├── chapter2.html
  ├── chapter3.html
  ├── chapter4.html
  ├── chapter5.html
  └── style.css
  body {
  font-family: Georgia, serif;
  line-height: 1.6;
  max-width: 700px;
  margin: 40px auto;
  padding: 0 15px;
  background: #fdfdfd;
  color: #222;
}

h1, h2, h3 {
  text-align: center;
  font-family: "Times New Roman", serif;
}

a {
  color: #0044cc;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

button {
  background: #444;
  color: white;
  padding: 10px 16px;
  border: none;
  cursor: pointer;
  border-radius: 4px;
}

button:hover {
  background: #222;
}localStorage.setItem("bookmark", "chapterX.html");
https://yourusername.github.io/mybook/
https://bookmaster.github.io/mybook/

}