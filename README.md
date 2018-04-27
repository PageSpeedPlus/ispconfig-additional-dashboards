# ISPConfig Additional Dashboards

## OPcache Statistik

```bash
cd /usr/local/ispconfig/interface/web
wget https://raw.githubusercontent.com/PageSpeed-Ninjas/ispconfig-additional-dashboards/master/opcache/opcache.php
chown -Rf ispconfig:ispconfig /usr/local/ispconfig/interface/web
chmod -Rf 750 /usr/local/ispconfig/interface/web
```

## Memecached Dashboard

```bash
cd /usr/local/ispconfig/interface/web
mkdir memecached
wget https://raw.githubusercontent.com/PageSpeed-Ninjas/ispconfig-additional-dashboards/master/memcached/index.php
chown -Rf ispconfig:ispconfig /usr/local/ispconfig/interface/web
chmod -Rf 750 /usr/local/ispconfig/interface/web
```

## Alo Server

Alo - Server Probe. A Light-weight PHP-Based Server Probe. Shows details of the hosting server.

* https://github.com/Asif2BD/Alo
* https://fastwp.de/8695/

### Installing/Configuring

```bash
cd /var/www/clients/client1/web1/web
wget https://raw.githubusercontent.com/Asif2BD/Alo/master/alo.php
chown -Rf client1:web1 /var/www/clients/client1/web1/web
```

## phpRedisAdmin

phpRedisAdmin is a simple web interface to manage Redis databases. It is released under the Creative Commons Attribution 3.0 license. This code is being developed and maintained by Erik Dubbelboer.

* https://github.com/erikdubbelboer/phpRedisAdmin

You can send comments, patches, questions here on github or to erik@dubbelboer.com.

### Example

You can find an example database at http://dubbelboer.com/phpRedisAdmin/

### Installing/Configuring

```bash
cd /var/www/clients/client1/web1/web
git clone https://github.com/ErikDubbelboer/phpRedisAdmin.git
cd phpRedisAdmin
git clone https://github.com/nrk/predis.git vendor
chown -Rf client1:web1 /var/www/clients/client1/web1/web
```


