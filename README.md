# open-odoo
this is repo to install the odoo customization for crm, sales, hr
# https://registry.hub.docker.com/_/odoo/
```
docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:10
```
```
docker run -p 8069:8069 --name odoo --link db:db -t odoo
```
```
http://localhost:8069/
```
# https://github.com/opsway/odoo-docker-extend
