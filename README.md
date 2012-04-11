A set of simple backup utilities, install them using the Makefile

    sudo make install

To setup a backed up location, run;

    lbrun -s /important/data -l /mnt/backup/backup-location -V setup

This will create two example configurations in;

    /important/data/.lbconf
    /important/data/.lbexcl

For an example cron definition, run;

    lbrun -s /important/data cron

*lbconf* is included as a convenience command to run a single command against a list of backup locations;

    lbconf /etc/backups.txt hourly

This project and all code released it is released public domain, have fun with it!
