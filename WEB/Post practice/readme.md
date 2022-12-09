Category: Web
Difficulty: Medium



- POST Practice

Description

This website requires authentication, via POST. However, it seems as if someone has defaced our site. Maybe there is still some way to authenticate? http://165.227.106.113/post.php


Answer:

1.goto the browser and put http://165.227.106.113/post.php.

2.view page source the page.

3.you have username & pass admin.

4.use the webshell get the terminal.

5.use curl with command " curl -X POST -d 'username=admin' -d 'password=71urlkufpsdnlkadsf' http://165.227.106.113/post.php.


Flag: flag{p0st_d4t4_4ll_d4y}
