# rolling
<?php
for ($count =1; $count<=4; $count++){
$roll1 = rand(1, 6);
$roll2 = rand(1, 6);
echo '<p>You rolled a ' . $roll1 . ' and a ' . $roll2
 . '</p>';

if ($roll1 == $roll2 ) {
 echo '<p>You win!</p>';
}
else {
 echo '<p>Sorry, you didn\'t win, better luck next time!</p>';
}
}
echo '<p>Thanks for playing</p>';

?>
