# monitor-ynh
A small infra monitoring tool

You need to install bc and redis-server.

You need to configure a cron like this:

```
# cat /etc/cron.d/monitor-ynh-cron
*/15  *  *  *  * USER /bin/bash /PATH/TO/monitor-ynh
```

Don't forget to give executable permissions to monitor-ynh script and test it.
