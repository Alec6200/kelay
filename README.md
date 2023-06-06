# kelay
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://Alec6200.github.io/kelay/index.html$1 [R,L]
