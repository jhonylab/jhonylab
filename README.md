<?php
$hostname_conex = "localhost";
$database_conex = "bahucom_emi";
$username_conex = "bahucom_emi";
$password_conex = "71935248628e";
$conex = mysqli_connect($hostname_conex, $username_conex, $password_conex, $database_conex); 
error_reporting(E_ALL);
ini_set("display_errors", 1);
mysqli_set_charset($conex, 'utf8');
?>
