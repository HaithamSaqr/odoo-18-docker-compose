# Installing Odoo 18.0 with one command (Supports multiple Odoo instances on one server).

## Quick Installation

Install [docker](https://docs.docker.com/get-docker/) and [docker-compose](https://docs.docker.com/compose/install/) yourself, then run the following to set up first Odoo instance @ `localhost:10018` (default master password: `P@ss@123`):

``` bash
cd /opt
curl -s https://raw.githubusercontent.com/HaithamSaqr/odoo-18-docker-compose/master/run.sh | sudo bash -s odoo18 10018 20018
```
and/or run the following to set up another Odoo instance @ `localhost:11018` (default master password: `P@ss@123`):

``` bash
cd /opt
curl -s https://raw.githubusercontent.com/HaithamSaqr/odoo-18-docker-compose/master/run.sh | sudo bash -s odoo18 11018 21018
```

