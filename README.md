# FreePBX on Docker (Raspberry Pi)

FreePBX container image for running a complete Asterisk server.

With this container you can create a telephony system in your office or house with integration among various office branches and integration to external VOIP providers with features such as call recording and IVR (interactive voice response) Menus.

### Image includes

 * Debian 9 Stretch with NodeJS 12
 * PHP 5.6
 * Legacy Debian Jessie MySQL ODBC Connector
 * Asterisk 16.4.0
 * Freepbx-14.0-latest
 * Opensource G729 v1.0.4
 * Modules: IVR, Time Conditions, Backup, Recording
 * Automatic backup script
 * Container size: approx 

### Run FreePBX image

* Run ```docker-compose up -d```
* Open web admin panel at your raspberry pi's ip-address


### Credits

* https://github.com/flaviostutz/freepbx
* https://github.com/tiredofit/docker-freepbx
* https://tecadmin.net/install-php-debian-9-stretch/
