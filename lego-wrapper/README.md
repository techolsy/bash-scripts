# Lego wrapper script

using for obtaining certifacte

example config to use

```bash
ACME_SERVER=http://acme.example.com
ACME_EMAIL=mail@example.com
KEY_TYPE=ec256
CHALLENGE=http # or tls
WEBROOT=/var/www/html
DEPLOY_CRT=root:root,644,/root/cert.crt
DEPLOY_KEY=root:root,644,/root/cert.key
UNIT_RELOAD=nginx.service
UNIT_RESTART=exim.service
```
