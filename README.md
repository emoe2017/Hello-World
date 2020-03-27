<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
   <?php
        $name = "Earl";
        $age = "68";

        echo "---- Hello ! $name's Web page --- <br>";
        echo "<hr>";
        echo "<p>This is my site</p <br>";
        echo "I am $age years old <br>";
        echo sqrt(144) ;
  ?>
 <form action="site.php" method="get">
   <br>
   Name: <input type="text" name="name">
   <br>
   <br>
   Age: <input type="number" name="age">
   <br>
   <br>
   <input type="submit">
 </form>
   <br>
    Your name is <?php echo $_GET["name"] ?>
    <br>
	<br>
    Your age is <?php echo $_GET["age"] ?>
    <br>
	<br>
		<?php
    	$friends = array("earl", "wayne", "moser", "wren");
    	array_push($friends, "the push?");
		echo "How many friends? - ";
    	echo count($friends);
		echo "<br>";
		echo "<br>";
		print_r($friends);
	?>

     </body>
    </html>




