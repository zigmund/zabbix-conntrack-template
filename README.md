# zabbix-conntrack-template
Zabbix template for collecting Linux conntrack metrics.

Usefull for monitoring systems doing NAT, for example - Docker/Kubernetes nodes, Linux-based gateways.

Uses system.run but may be altered with userparameter if remote commands are forbidden. Ubuntu Xenial< and Debian Stretch< tested, but may also work on other distro.

Some of the features:
* Single request.
* Minimum host dependencies - lnstat (part of iproute2 package) used.
* No host scripts, only system.run and dependent items.
