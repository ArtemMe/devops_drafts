# devops_drafts
It is repo with drafts infrastructure application such as nginx, databases etc

## NGINX with proxy pass and https
There are some example how to redirect https traffic to another server.     
Some tips:
* Don`t forget about proxy_ssl_server_name instruction that can allow you to redirect https traffic
* Don`t forget about slash in upstream (https://stackoverflow.com/questions/41609509/nginx-reverse-proxy-return-404?rq=1)