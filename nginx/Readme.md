

###  Bugs 
####  How can we write correct way for phpMyAdmin

```
upstream php {
  server phpmyadmin:80;
}

location /phpmyadmin {
    proxy_pass http://php;
}
```