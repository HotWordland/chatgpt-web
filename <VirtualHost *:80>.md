<VirtualHost \*:80>

ServerName chat.wonderlandprotech.xyz

ServerAlias chat.wonderlandprotech.xyz

ProxyPreserveHost On

ProxyRequests Off

# 代理重定向地址

ProxyPass / http://localhost:8080

ProxyPassReverse / http://localhost:8080

</VirtualHost>
