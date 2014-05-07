## RackSpace Cloud Server + Magento + httpd + php + varnish + mysql Deployment<br />
This playbook will create:<br />
1. Rackspace Load Balancer.<br />
2. Rackspace Cloud Servers (1 master and multiple slaves) for LAMP and lsync.<br />
3. Rackspace Cloud Server for MySQL.<br />
4. Install Magento.<br />
5. Add WEB servers to LB.<br />
<br />
Change rax.py to set your username and api_key.<br />
Change configurations on group_vars/all to define hostname, domain, users, admin, etc.<br />
