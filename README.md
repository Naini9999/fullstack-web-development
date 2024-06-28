<!DOCTYPE html>
<html>
<head>
    <title>Interactive Elements with JavaScript</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>

<h1>Interactive Elements with JavaScript</h1>

<nav>
    <ul id="menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>

<h2>Validation Form</h2>
<form name="myForm" onsubmit="return validateForm()" method="post">
    Name: <input type="text" name="fname">
    <input type="submit" value="Submit">
</form>

<div id="dynamic-content">
    <p>This content will change when you click the button below.</p>
    <button onclick="updateContent()">update content</button>
</div>

</body>
</html>
