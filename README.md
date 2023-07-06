# HMS-CFG
Config files for my home media server setup

Note: SWAG uses NGINX as a server

Some services like ai image generation are currently not deployed.
![image](https://github.com/pomee4/HMS-CFG/assets/13985863/083e86be-e2d7-47ce-97e8-4d235dda8c26)

Content is set up to be served trough Cloudflare's DNS tunneled trough a DDNS provider, while also using letsencrypt SSL.
![image](https://github.com/pomee4/HMS-CFG/assets/13985863/56ed1be1-a705-4e94-bccb-4c05b8a78e8d)

The content is reachable at https://pomee.hu , also some content are rendered unavailable from remote access due to security reasons, most services require authentication to use.
![image](https://github.com/pomee4/HMS-CFG/assets/13985863/9ca9bdff-35ff-4f62-85ae-e779bf059c03)

To-Do:
Fail2Ban and Authentik setup is currently under work.
