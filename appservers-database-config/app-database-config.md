## Create a Database config file in the application servers 
vi dbinfo.inc

## Copy and Past the Below Data in the file after updating
```bash
<?php

define('DB_SERVER', 'database-1.cro04uway71v.me-south-1.rds.amazonaws.com');
define('DB_USERNAME', 'admin');
define('DB_PASSWORD', '15900*MandelaC');
define('DB_DATABASE', 'phpappdatabase');

?>
```
