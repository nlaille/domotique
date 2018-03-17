# domotique

## FAQ

1. Probleme de compilation d'un module python

https://community.home-assistant.io/t/error-starting-home-assistant-on-synology-for-first-time/917/9

```bash
bash$ sudo /var/package/debian-chroot-scripts/start-stop-status chroot
chroot$ apt-get install [module]
chroot$ pip3 install [module]
chroot$ exit
bash$ cd /volume1/@appstore/py3k/usr/local/lib/python3.5/site-packages/
bash$ cp /usr/local/debian-chroot/var/chroottarget//usr/local/lib/python3.5/dist-packages/* . -R
```

