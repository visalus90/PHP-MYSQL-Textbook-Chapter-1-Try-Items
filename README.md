Student Name: Bailey McKay <br>
Class: 2023 Fall Term Introduction to PHP DGL-123<br>
Repository Link: https://github.com/visalus90/PHP-MYSQL-Textbook-Chapter-1-Try-Items.git

<?php
$name      = 'Ivy';
$favorites = ['Chocolate', 'Toffee', 'Fudge',];
?>
<!DOCTYPE html>
<html>
  <head>
    <title>Echo Shorthand</title>
    <link rel="stylesheet" href="css/styles.css">
  </head>
  <body>
    <h1>The Candy Store</h1>
    <h2>Welcome <?= $name ?></h2>
    <p>Your favorite type of candy is:
      <?= $favorites[0] ?></p>
  </body>
</html>



