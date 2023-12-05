<?php
$server = "database-2.cxieft7kvftt.ap-south-1.rds.amazonaws.com";
$username = "admin";
$password = "12345678";
$database = 'users';

$conn = mysqli_connect($server, $username, $password, $database);
if (!$conn){
//     echo "success";
// }
// else{
    die("Error". mysqli_connect_error());
}

?>
