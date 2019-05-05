# zSL142 Server Status

Minecraft Java Server Status for Web Developer 

## Usage

```php
<?php
include "./zStatus.php";

$ip = "mc-seksin.net"; //ip server here

$server = new zSL142($ip,25565);
$var = $server->online;

$player = $server->online_player; //Player Online
$max_player = $server->max_player; //Max Player 

if($var == 1){
    $status = "online"; //Status Online
}else{
    $status = "ofline"; //Status Ofline
}


echo "Status : ".$status."<br>"; //Show Status 
echo "Online Player : ".$player."/".$max_player; //Show Online Player
```

## SL142
[Facebook](https://fb.me/iboy.sloth.1)
-
