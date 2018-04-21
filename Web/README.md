## Logmein1 бие халаалт (5pts)

http://218.100.84.112:9000
> **By reamb**

## Logmein2 (10pts)

http://218.100.84.112:9003
> **By reamb**

## Hacker Academy 1 (10pts)

Hacker Academy -д тавтай морил.  
Төгс довтолгоо таны гарт.  
http://218.100.84.112:9101
> **By W01f**

## Logmein3 (50pts)

http://218.100.84.112:9001
> **By Ds3c**

## Hacker Academy 2 (60pts)

Энд туг 2-ийг оруулна уу.

> Hint! Флагыг хаана байршиж байгааг мэдэхийн биш биз?  
> Hint! OTG-AUTHZ-001  
> **By W01f**

## Baby Web (65pts)

http://218.100.84.112:9004

```html
<html>
<head>
<title>BigNumber</title>
<link rel='stylesheet' href='style.css' type='text/css'>
</head>
<body>

<?php
require 'flag.php';
if (isset($_GET)) {
if (is_numeric($_GET)){
if (strlen($_GET) < 4){
if ($_GET > 999)
die('Flag: '.$flag);
else
print '<p class="alert">Baga bna, Tom Bai</p>';
} else
print '<p class="alert">Tom bna, Baga bai</p>';
} else
print '<p class="alert">No Number, No Cry</p>';
}
?>

<section class="login">
<form method="get">
<input type="text" required name="too" placeholder="Numbers Only" /><br/>
<input type="submit"/>
</form>
</section>
</body>
</html>

```
> **By W01f**

## Logmein4 (100pts)

http://218.100.84.112:9002
> **By reamb**
