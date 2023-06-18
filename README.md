# nginx-basics
Basic rules for creating an NGINX server

1. All virtual servers should be listed in "sites-available" directory, then its contents must be linked to "sites-enabled" directory: `ln -s /etc/nginx/sites-available/* /etc/nginx/sites-enabled/`
2. Reusable rules may be contained in "/etc/nginx/<folder_name>" folder and later `included` in NGINX configs.
