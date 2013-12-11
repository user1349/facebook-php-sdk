<?php
require 'src/facebook.php';
 
// Create our Application instance (replace this with your appId and secret).
$facebook = new Facebook(array(
  'appId' => '2324983201930103',
  'secret' => 'f5wjeu72hmxjf981da84jpwo02sdvge3',
));
 
$theRequest = $facebook->getSignedRequest();
 
if($theRequest["page"]["liked"] == 1){
    echo "The real content";
}
else{
    echo "Like our page to view";
}
?>
