# Flag Format
## Category: Web
## Problem Statement
> when php, anime and robots come together. they make hell of a challenge. https://uwu.vishwactf.com/
## Hints
> php, anime, ROBOTS
## Solution
Kunjungi website yang tertera, namun berikan subfolder sesuai dengan hint yang ada
![image](https://user-images.githubusercontent.com/57520495/111195705-1e7b3100-85ef-11eb-9e81-aa63e98854c9.png)
Di dalam link tersebut, terdapat sebuah program PHP yang akan menghasilkan flagnya
```<!DOCTYPE HTML>
<?php
  require("cyberflagster.php");  
  $try; //1
  $function; //5
  if (isset($_GET['showThem'])) {
   
    highlight_file(__FILE__);
   
    die();
  
  }
   $reach;//3
  if (isset($_GET['php_is_hard'])) {
  
    $you_enter = $_GET['php_is_hard'];
  
    $we_enter = 'suzuki_harumiya';
  
    $the_final_one = preg_replace(
    
      "/$we_enter/", '', $you_enter);
  
      if ($the_final_one === $we_enter) {
  
        open_up();
    }
  }
  $to; //2
  $open_up;//4
?>

<html>
  <head>
    <title>VishwaCTF-mini | web-php-1</title>
  </head>
  <body style="background-color:#121212">
  <h1>Try Solving this normie<h1>
  <a target="_blank" href="?showThem"><h3>Source Code</h3></a>

  </body>
</html>
```
Jawaban akhirnya adalah
`https://uwu.vishwactf.com/robots/?php_is_hard=suzuki_harusuzuki_harumiyamiya`
## Flag
great, here it is what your looking for=> `vishwaCTF{well_this_was_a_journey}`
