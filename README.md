# Minimal Linux Mint

Run `minimal-script.sh` to purge Linux Mint down to a minimal state.

Run `personal-script.sh` to purge software, leaving the pre-installed software that use daily.

Before running any of these scripts, please refer to the associated text file to determine what packages are removed from the system.

As of 2026-08-24, running the minimal bash script on a new Linux Mint install (22.3 Cinnamon) there are __XXXX__ software packages installed, if git has been installed. ( `apt list --installed | wc -l` )

- You may also run `sudo rm -r /etc/libreoffice/registry/res  \` in the terminal, as it was not removed due to not being empty.
