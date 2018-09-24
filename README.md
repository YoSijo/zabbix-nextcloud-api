# zabbix-nextcloud-api

Nextcloud Monitoring API integration for Zabbix 3.4

Needs curl to be installed on the Nextcloud server.

Set the Adminuser/PW in the Macros according to your needs.

For non-SSL requests on port 80 change item "Nextcloud Monitoring API" to http instead of https

Shows different operating values of your Nextcloud server:

Version, Webserver, Database Type, Database Version, Database Size, PHP Max. Execution Time, PHP Memory Limit, PHP Upload Max. Filesize, PHP Version, Storage Files, Storage Freespace, Storage Users, Number of Storages, Apps Installed, Apps Needing Update
