<?php
$ip = $_SERVER['REMOTE_ADDR'];


// Here The Script Take The IP Of The Visitor And Save It In blocked_ips.txt 
$ip = $_SERVER['REMOTE_ADDR'];
$myfile = fopen("blocked_ips.txt", "a+") or die("Unable to open file!");
$txt = "$ip\n";
fwrite($myfile, $txt);
fclose($myfile);

// Here In This Script It Take The IP ( Read The All Ip  ) 
// EX :  127.0.0.1 It The IP Of VISITOR if 127.0.0.1 In blocked_ips.txt The Script Banned This IP
if ( !file_exists('blocked_ips.txt') ) {
 $deny_ips = array(
  '127.0.0.1',
  '192.168.1.1',
  '83.76.27.9',
  '192.168.1.163'
 );
} else {
 $deny_ips = file('blocked_ips.txt');
}
// read user ip adress:
$ip = isset($_SERVER['REMOTE_ADDR']) ? trim($_SERVER['REMOTE_ADDR']) : '';
 
// search current IP in $deny_ips array
if ( (array_search($ip, $deny_ips))!== FALSE ) {
 // address is blocked:
 echo 'Your IP adress ('.$ip.') was blocked!';
 exit;
}
?>
