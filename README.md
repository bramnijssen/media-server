# media-server

## Synology prerequisites

On some Synology devices, you must install the `tun` kernel module on your host at every boot. To do so, open a terminal and enter:

```sh
sudo insmod /lib/modules/tun.ko
```

Add this command as a scheduled task to run at every boot.
