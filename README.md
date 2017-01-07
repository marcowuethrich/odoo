Requirements:
----

ubuntu 14.04 or higher


Install Odoo 9
----

* sudo apt-get install git
* sudo git clone https://github.com/marcowuethrich/odoo --depth 1 --single-branch odoo/odoo-server/

* sudo chmod +x odoo/odoo-server/odoo_install.sh
* odoo/odoo-server/odoo_install.sh



Customer Changes
----

Change the folder /odoo/odoo-server with the custom-Github repo (Main Programm Odoo and Server)

Change the folder /odoo/custom with the actual Backup order (Customer addons)


Run
---

sudo service odoo-server {start|stop|restart|force-reload}