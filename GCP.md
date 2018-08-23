# Pi-hole on Google Cloud Platform

# Draft
- Create an account and Setup Billing for your 1 year free trial
- Create a Project and link it to billing
- Configure firewall rules and static external IP address
- Create an Instance Template
  - Configure network tags to link firewall rules
  - Confifure metadata to set the hostname
- Create an instance from the template
- Set the hostname via cron when it reboots, calls the metadata via api
- Harden the server with UFW and install auto updates
```
$ curl -sSL https://install.pi-hole.net | bash
```
- Blocking modes (null, ip, ipv6, etc.)
  - Do you want a block page?
- Fix /var/www/html/pihole/index.php
- Le wildcard certificates
- Cron jobs (again)
- Bash scipts
