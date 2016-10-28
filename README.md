# Load Logger Script

This script logs the load of a server every X minutes. You can define the X within your cronjob.
So possibly you could log every minute (beware of huge log files!)

The usage is easy:

* Copy the script to any place on your server or clone it:

    git clone 

* If the permission is lost chmod it:

    chmod +x load_logger

* Then create a cronjob like this (every 5 minutes):

    */5 * * * * /path/to/load_logger

That's it! You can just delete the script and the cron when you don't need it anymore or just disable
the cron for a usage later.
