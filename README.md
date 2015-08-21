<img class="transparent" alt="http://2.bp.blogspot.com/-_x2Ug2pyR0U/UaerbBhqLGI/AAAAAAAACck/ThjI9aHQ_0E/s1600/banned.png" src="http://2.bp.blogspot.com/-_x2Ug2pyR0U/UaerbBhqLGI/AAAAAAAACck/ThjI9aHQ_0E/s1600/banned.png">
# block Multi IP Just By FILE.TXT

Hello Bro Today I Want To Show Easy method For Banned More Than ip Automatical 

<h3>#1 Edit Script </h3>
First Go To Index.php i Search (blocked_ips.txt) You Will Find It In Line Number 7 
You Can Change To Any Name !! . But You Need To Change All The Script For Example

1 - Change The Name <h6>We Preferre To Dont Change Any Thing ;) </h6>
$myfile = fopen("listofbanned.txt", "a+") 

and in line number 14
if ( !file_exists('listofbanned.txt') ) {

also In The Line Number 22
$deny_ips = file('listofbanned.txt');

