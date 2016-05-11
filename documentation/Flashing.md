# Flashing

On host

```sh
Flashing.1 > cd $HOME/intro/poky/scripts/contrib/
Flashing.2> # Place your USB Stick into your host and locate the device!
```

if you were able to build

```sh
flashing.3>./mkefidisk.sh /dev/sdb /home/lsandov1/build/tmp/deploy/images/intel-corei7-64/core-image-minimal-intel-corei7-64.hddimg /dev/sda
```

else flashing.

```sh
3>./mkefidisk.sh /dev/sdb /home/lsandov1/intro/images/core-image-minimal-intel-corei7-64.hddimg /dev/sda
```