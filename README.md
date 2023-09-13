Student Name: Bailey McKay <br>
Class: 2023 Fall Term Introduction to PHP DGL-123<br>
Repository Link: https://github.com/visalus90/PHP-MYSQL-Textbook-Chapter-1-Try-Items.git

<?php
$item       = 'chocolate';
$stock      = 3;
$wanted     = 5;
$deliver    = true;
$can_buy    = (($wanted <= $stock) && ($deliver == true));
?>
<!DOCTYPE html>
<html>
  <head> ... </head>
  <body>
    <h1>The Candy Store</h1>
    <h2>Shopping Cart</h2>
    <p>Item: <? $item ?></p>
    <p>Stock: <? $stock ?></p>
    <p>Ordered: <? $wanted ?></p>
    <p>Can buy: <? $can_buy ?></p>
  </body>
</html>
