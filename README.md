### dynamicVH
### Create VirtualHost for Apache 


Available for: [![](https://img.shields.io/badge/OS-Ubuntu-orange?style=flat&logo=linux&logoColor=black)](https://ubuntu.com/)

#### Script prompt you to enter:
* VirtualHost name (ex:  my_Virtual_Host)
* ServerName
* ServerAlias (ex: virtual_host.local)
* Apache Document Root: (ex: /var/www/html)
* Server Admin email 
* Error Log name
* Custom Log name
* IP Server (ex 127.0.0.1)
* Absolute path of of your project


#### What it does:

* Create conf into apache site-available/,
* Create symbolic link in Document Root
* append local server name on hosts file,
* enable site 
* reload apache
_____
* List enabled sites







```

     _                                  _                         
  __| | _   _  _ __    __ _  _ __ ___  (_)  ___   /\   /\   /\  /\
 / _` || | | || '_ \  / _` || '_ ` _ \ | | / __|  \ \ / /  / /_/ /
| (_| || |_| || | | || (_| || | | | | || || (__    \ V /  / __  / 
 \__,_| \__, ||_| |_| \__,_||_| |_| |_||_| \___|    \_/   \/ /_/  
        |___/                                                     

                                                    Powered by Alfonso with ❤ 
    

    Usage: vh [options] [args...]

    -s               Start program
    -l               List sites enabled
    -v               Version number
    -h               This help

```
