# containers

runc configs for containers.

You can run any of these with the systemd service file
[runc@.service](runc@.service) in this repo like so:

```console
# just pass a directory name
$ sudo systemctl start runc@notify-osd

$ sudo systemctl start runc@chrome
```
