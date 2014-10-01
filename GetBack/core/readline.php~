<?php


class readfile
{


function searchdate()
{


$myfile="/var/log/apt/history.log";
$search      = "autoremove";
$lines       = file($myfile);
$line_number = false;




while (list($key, $line) = each($lines) and !$line_number) {
   $line_number = (strpos($line, $search) !== FALSE) ? $key + 1 : $line_number;

//echo $line_number;
}

if(!empty($line_number))
{


//$myfile="file.txt";
$lines = file($myfile);//file in to an array

 $result=$lines[$line_number];
return $result;

}
else
{
echo $result="X";
//return $result;
}

}


}
?>
