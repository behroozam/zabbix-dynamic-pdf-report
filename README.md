zabbix-dynamic-pdf-report
=========================


This originates from https://github.com/spy86/Zabbix_/zabbix-dynamic-pdf-report that not exist anymore

Also to make sure it works 100% with Zabbix 3.2 ( not older version)


Installation
------------
```
#copy zabbix-dynamic-pdf-report to zabbix frontend directory by default is /usr/share/zabbix
sudo cp zabbix-dynamic-pdf-report /usr/share/zabbix
# set Permissions
sudo chown -R www-data: /reports /tmp
#copy sample to real config
cp config.inc.sample.php config.inc.php

#edit to match your environment
nano config.inc.php

```


develop
-------

* clone `https://github.com/behroozam/zabbix-dynamic-pdf-report`
* Install PHP `sudo apt-get install php7.0 php7.0-cli php7.0-curl php7.0-json`
