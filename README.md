Virtualization scripts
==============

Some bash scripts used to manage Citrix XenServer by the CPD/UFRGS team

* ufrgs-convert - Converts Citrix XenServer virtual machines between PV and HVM modes

* ufrgs-vm-reports - generate memory and disk usager report

* ufrgs-autostart - set the autostart properties on tagged virtual machines

# Installation

Copy the scripts to /usr/local/bin/ folder. Don't forget to chmod +x them.

The ufrgs-autostart can be scheduled to run hourly copying the cron configuration file to the /etc/cron.d/ folder.