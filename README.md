Student Name: Bailey McKay <br>
Class: 2023 Fall Term Introduction to PHP DGL-123<br>
Repository Link: https://github.com/visalus90/PHP-MYSQL-Textbook-Chapter-1-Try-Items.git

<?php
$items         = 5;
$cost          = 12;
$subtotal      = $cost * $items;
$tax           = ($subtotal / 100) * 20;
$total         = $subtotal + $tax;
?>
<!DOCTYPE html>
<html>
  <head> ... </head>
  <body>
    <h1>The Candy Store</h1>
    <h2>Shopping Cart</h2>
    <p>Items: <?= $items ?></p>
    <p>Cost per pack: $<?=$cost ?></p>
    <p>Subtotal: $<?= $subtotal ?></p>
    <p>Tax: $<?= $tax ?></p>
    <p>Total: $<?= $total ?></p>
  </body>
</html>
