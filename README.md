# ISPConfig Additional Dashboards

## Alo Server

Alo - Server Probe. A Light-weight PHP-Based Server Probe. Shows details of the hosting server.

* https://github.com/Asif2BD/Alo
* https://fastwp.de/8695/

### Installing/Configuring

```bash
cd "/var/www/web/ispconfig/"
wget https://raw.githubusercontent.com/Asif2BD/Alo/master/alo.php
chown -r ispconfig:ispconfig /var/www/web/ispconfig/
```

## phpRedisAdmin

phpRedisAdmin is a simple web interface to manage Redis databases. It is released under the Creative Commons Attribution 3.0 license. This code is being developed and maintained by Erik Dubbelboer.

* https://github.com/erikdubbelboer/phpRedisAdmin

You can send comments, patches, questions here on github or to erik@dubbelboer.com.

### Example

You can find an example database at http://dubbelboer.com/phpRedisAdmin/

### Installing/Configuring

```bash
cd "/var/www/web/ispconfig/"
git clone https://github.com/ErikDubbelboer/phpRedisAdmin.git
cd phpRedisAdmin
git clone https://github.com/nrk/predis.git vendor
chown -r ispconfig:ispconfig /var/www/web/ispconfig/
```


