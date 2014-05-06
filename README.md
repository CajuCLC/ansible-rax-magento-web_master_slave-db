## RackSpace Cloud Server + Magento + httpd + php + varnish + mysql Deployment
This playbook will create:
1. Rackspace Load Balancer.
2. Rackspace Cloud Servers (1 master and multiple slaves) for LAMP and lsync.
3. Rackspace Cloud Server for MySQL.
4. Install Magento.
5. Add WEB servers to LB.

Change rax.py to set your username and api_key.
Change configurations on group_vars/all to define hostname, domain, users, admin, etc.