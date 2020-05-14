# zabbix-conntrack-template
Zabbix template for collecting Linux conntrack metrics.

Uses system.run but may be altered with userparameter if remote commands are forbidden. Ubuntu Xenial< and Debian Stretch< tested, but may work of other distro.

Some of the features:
* Single request.
* Minimum host dependencies - lnstat (part of iproute2 package) used.
* No host scripts, only system.run and dependent items.
