# **`🚀 HTML TAGS (At A Glance)`**

```html
1. <!DOCTYPE>
2. <html>
3. <head>
4. <title>
5. <meta>
6. <link>
7. <style>
8. <script>
9. <body>
10. <h1> to <h6>
11. <p>
12. <br>
13. <hr>
14. <a>
15. <img>
16. <strong>
17. <em>
18. <small>
19. <mark>
20. <del>
21. <ins>
22. <sub>
23. <sup>
24. <div>
25. <span>
26. <ul>
27. <ol>
28. <li>
29. <table>
30. <thead>
31. <tbody>
32. <tfoot>
33. <tr>
34. <td>
35. <th>
36. <form>
37. <input>
38. <textarea>
39. <button>
40. <select>
41. <option>
42. <label>
43. <fieldset>
44. <legend>
45. <iframe>
46. <nav>
47. <header>
48. <footer>
49. <main>
50. <section>
51. <article>
52. <aside>
53. <figure>
54. <figcaption>
55. <details>
56. <summary>
57. <audio>
58. <video>
59. <source>
60. <canvas>
61. <noscript>
62. <embed>
63. <object>
64. <abbr>
65. <address>
66. <cite>
67. <code>
68. <pre>
69. <q>
70. <blockquote>
71. <time>
72. <progress>
73. <meter>
```

___


# **`🧱 BLOCK LEVEL TAGS`**

```html
1. <html>
2. <head>
3. <body>
4. <div>
5. <p>
6. <h1> to <h6>
7. <hr>
8. <pre>
9. <blockquote>
10. <ul>
11. <ol>
12. <li>
13. <table>
14. <thead>
15. <tbody>
16. <tfoot>
17. <tr>
18. <td>
19. <th>
20. <form>
21. <fieldset>
22. <legend>
23. <section>
24. <article>
25. <aside>
26. <nav>
27. <header>
28. <footer>
29. <main>
30. <figure>
31. <figcaption>
32. <address>
33. <canvas>
34. <video>
35. <audio>
36. <noscript>
```

# **`🧩 INLINE-LEVEL TAGS`**

```html
1. <a>
2. <img>
3. <br>
4. <strong>
5. <em>
6. <small>
7. <mark>
8. <del>
9. <ins>
10. <sub>
11. <sup>
12. <span>
13. <label>
14. <input>
15. <textarea>*
16. <button>
17. <select>
18. <option>
19. <abbr>
20. <cite>
21. <code>
22. <q>
23. <time>
24. <script>
25. <meta>
26. <style>
27. <title>
28. <link>
29. <source>
30. <embed>
31. <object>
```


____

# **`🧱 BLOCK-LEVEL TAGS (Grouped by Topic)`**

### 📄 Document Structure

* `<html lang="en">`: The root element of an HTML document. Wraps the entire HTML content.
* `<head>`: Contains metadata, title, styles, and scripts. Not displayed on the page.
* `<body>`: Contains the visible content of the web page.
* `<title>`: Sets the title shown in the browser tab.
* `<meta charset="UTF-8">`: Provides metadata like character set, author, and viewport settings.
* `<link rel="stylesheet" href="style.css">`: Links external resources like CSS files.
* `<style type="text/css">`: Embeds internal CSS styles.
* `<script type="text/javascript">`: Adds or links to JavaScript for interactivity.

### 🧾 Text & Layout

* `<div class="container">`: A generic container for grouping elements. Used for layout and styling.
* `<p>`: Defines a paragraph of text.
* `<h1 id="main-title">` to `<h6>`: Define headings, with `<h1>` being the most important.
* `<hr>`: Inserts a horizontal rule (line), used to separate content.
* `<pre>`: Displays preformatted text preserving whitespace and line breaks.
* `<blockquote cite="source.html">`: Indicates a section that is quoted from another source.
* `<address>`: Provides contact information for a person or organization.

### 📋 Lists

* `<ul>`: Unordered list (bulleted).
* `<ol type="1">`: Ordered list (numbered).
* `<li>`: List item inside `<ul>` or `<ol>`.
* `<dl>`: Description list. Used to pair terms and descriptions.
* `<dt>`: Term/name in a description list.
* `<dd>`: Description/details of the term in a description list.

### 📊 Tables

* `<table border="1">`: Defines a table.
* `<thead>`: Groups header content in a table.
* `<tbody>`: Groups body content in a table.
* `<tfoot>`: Groups footer content in a table.
* `<tr>`: Table row.
* `<td colspan="2">`: Table cell (data).
* `<th scope="col">`: Table cell (header).

### 📦 Semantic Layout

* `<header>`: Represents introductory content or navigational links.
* `<footer>`: Contains footer content like copyright or contact info.
* `<main>`: Represents the main content of the document.
* `<nav>`: Container for navigation links.
* `<section>`: Groups related content under a theme.
* `<article>`: Represents a self-contained piece of content (like a blog post).
* `<aside>`: Sidebar content or tangentially related information.
* `<figure>`: Groups media content like images or illustrations.
* `<figcaption>`: Caption for a `<figure>` element.

### 🧾 Forms

* `<form action="/submit" method="post">`: Defines a form to collect user input.
* `<fieldset disabled>`: Groups related elements in a form.
* `<legend>`: Provides a caption for a `<fieldset>`.

### 🖼️ Media

* `<canvas width="300" height="150">`: Used to draw graphics via scripting (like JavaScript).
* `<video controls src="video.mp4">`: Embeds a video player.
* `<audio controls src="audio.mp3">`: Embeds an audio player.
* `<noscript>`: Content shown if JavaScript is disabled in the browser.

---

# **`🧩 INLINE-LEVEL TAGS (Grouped by Topic)`**

### 🔤 Text Formatting

* `<span class="highlight">`: Generic inline container. Useful for styling specific text.
* `<strong>`: Indicates strong importance. Typically bold.
* `<em>`: Emphasizes text. Typically italic.
* `<small>`: Displays text in a smaller font.
* `<mark>`: Highlights text.
* `<del datetime="2020-01-01">`: Represents deleted text.
* `<ins datetime="2020-01-02">`: Represents inserted text.
* `<sub>`: Subscript text (e.g., H₂O).
* `<sup>`: Superscript text (e.g., x²).
* `<abbr title="HyperText Markup Language">`: Abbreviation. Displays a tooltip on hover.
* `<cite>`: Cites a creative work.
* `<code>`: Displays inline code.
* `<q cite="source.html">`: Short inline quotation.
* `<time datetime="2025-06-23">`: Represents a date/time value.

### 🔗 Links & Navigation

* `<a href="https://example.com" target="_blank">`: Defines a hyperlink to another page or location.

### 🖼️ Media & Embeds

* `<img src="image.jpg" alt="description">`: Embeds an image.
* `<br>`: Line break. Moves content to a new line.
* `<source src="media.mp4" type="video/mp4">`: Specifies media resources for `<video>` or `<audio>`.
* `<embed src="file.pdf" type="application/pdf">`: Embeds external content like PDFs or Flash.
* `<object data="file.swf" type="application/x-shockwave-flash">`: Embeds objects like multimedia or applets.
* `<iframe src="https://example.com" width="600" height="400">`: Embeds another webpage inside the current one.

### 🧾 Forms

* `<label for="input-id">`: Defines a label for an input element.
* `<input type="text" name="username" placeholder="Enter username">`: User input control (text, checkbox, etc).
* `<textarea name="message" rows="4" cols="50">`: Multi-line text input.
* `<button type="submit">`: Clickable button.
* `<select name="dropdown">`: Dropdown list.
* `<option value="1">`: Options inside a `<select>` dropdown.

### ⚙️ Metadata & Scripts

* `<style type="text/css">`: Embeds CSS styles inline.
* `<script type="text/javascript">`: Embeds JavaScript inline.
* `<link rel="stylesheet" href="style.css">`: Links to external files (like stylesheets).
* `<meta charset="UTF-8">`: Defines metadata.
* `<title>`: Sets the document's title.

___
 
# ***`Teaching Pedagody : HTML TAGS GROUPED BY TOPICS`***