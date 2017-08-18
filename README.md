# Linux Server Configuration Project (Udacity)
Udacity nano-degree course focused on configuring a linux server and loading a prior project (item catalog) onto the server.

## IP Address
34.231.103.192

## URL
http://ec2-34-231-103-192.compute-1.amazonaws.com/

## Software Installed
* Finger
* Python
* Apache2
* PostgreSQL
* git

## Configurations Made
* Disabled password login and switched to key login (with passphrase).
* Enabled remote SSH from port 2200.
* Created firewall (UFW) for SSH, NTP (123), and HTML (80).
* Switched timezone to UTC.
* Installed and configured Apache according to Udacity Linux Configuration class, lesson 6.  Configured Apache to serve a mod_wsgi file.
* Installed Python mod-wsgi application files.
* Installed git and loaded the [Item Catalog](https://github.com/deepanjan1/item_catalog) application .  Configured mod-wsgi to load the Item Catalog application.
* Created a new client_secrets file to direct to the static IP (as mentioned above).
* Set .git to not be publically accessible.

## Sources Used
* Udacity Forums
* [SQLAlchemy Engine Configuration](http://docs.sqlalchemy.org/en/latest/core/engines.html#postgresql)
* [Postgres Basic Server Setup](https://help.ubuntu.com/community/PostgreSQL#Basic_Server_Setup)
* [Digital Ocean: How To Deploy a Flask Application on an Ubuntu VPS](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
