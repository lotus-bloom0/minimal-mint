# Minimal Linux Mint

Run `minimal-script.sh` to purge Linux Mint down to a more minimal state. The list from the forked repository seems to be quite dated and will need to be updated at some point.

Run `personal-script.sh` leaves only the pre-installed software and system tools that I use.

Before running any of these scripts, please refer to the associated text file to determine what packages will be removed from the system.

As of 2026-08-24, running the minimal bash script on a new Linux Mint install (22.3 Cinnamon) there are __1845__ software packages installed, if git has been installed. ( `apt list --installed | wc -l` )
