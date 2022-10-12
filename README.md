# PHP Basic

### <u>What is PHP </u>

- `PHP` Stand for `Hypertext preprocessor`
- PHP is a `server side scripting Language`

#### **PHP Syntax**
```php
<?php

?>
```

<details>
  <summary>Frist PHP Code</summary>

In PHP dispaly anythis use `echo`
```php
<?php
echo "Hello World"
?>
```
</details>
<details>
  <summary> PHP Variable</summary>

- In PHP use variable `$` Symbole<br>
`$userName` = "Sakil Khan"<br>
`myNumber` = 40;

```php
<?php
$userName = "Shakil Khan";
echo $userName;
?>
```
```php
<?php
$myNumber = 40;
echo $myNumber;
?>
```
```php
<?php
$num_1 = 40;
$num_2 = 20;
$sum = $num_1 + $num_2
echo "The Sumation is: ".$sum; //. is concatination in php
?>
```
</details>
<details>
  <summary> If...Else Condition</summary>

```php
<?php
$rainFall = true;
if(rainFall) {
  echo "Today is Raining";
} else {
  echo "Today is Not Raining".
}
?>
```
</details>
<details>
  <summary> Else...If Condition</summary>

```php
<?php
$color = "green";
if(color == "green") {
  echo "Light is Green";
} else if (color == "red") {
  echo "Light is Red";
} else if (color == "yellow") {
  echo "Light is Yellow";
} else {
  echo "Light is not Matching";
}
?>
```
</details>
<details>
  <summary> Funciton</summary>

- There are Two types of Funciton<br>
`In-build` function   <br>
`User-defined` function

```php
<?php
function userName() {
  echo "My Name is Mahbubul Alam";
}
userName();
?>
```
```php
<?php
function userName($name) {
  echo $name;
}
userName("My Name is Mahbubul Alam");
userName("I am Sirazul Islam");
userName("I am alo Ashikul Haque");
?>
```
```php
<?php
function sumNumber($num_1, $num_2) {
  echo $num_1 + $num_2 ;
}
sumNumber(40, 23);
?>
```
</details>
<details>
  <summary> Loop </summary>

- For Loop  use one item many time call<br>


```php
<?php
for ($i = 0; $i < 5; $i++) {
  echo "<h2>Pakistan<h2>"; 
}
?>
```
</details>
<details>
  <summary> Array </summary>

`array` `[]`<br>
Arry are using `array` and `[]`  symbole


```php
$useName = array("Sakib", "Nakib", "Sirajul", "Milon");
echo $userName[0]."<br>";
```
```php
$useName = array("Sakib", "Nakib", "Sirajul", "Milon");
foreach($userName as $name) {
  echo $name."<br>";
}
```
</details>


