#QEMU

##Cloning and Running

* [Source](http://wiki.qemu.org/Download Download Source)
* [Building Source](http://wiki.qemu.org/Hosts/Linux Qemu-Wiki) 

##Build Commands

Custom build commands for minimal kernel

```bash
$ ./configure --target-list=x86_64-softmmu --enable-debug --disable-werror --disable-slirp --disable-blobs --disable-gnutls --disable-sdl --disable-gtk --disable-vte --disable-cocoa --disable-virtfs --disable-xen --disable-xen-pci-passthrough --disable-brlapi --disable-bluez --disable-netmap --disable-rbd --disable-libiscsi --disable-libusb --disable-usb-redir --disable-snappy --disable-glusterfs --disable-archipelago --disable-vhdx --disable-numa

$ sudo make -j8

$ sudo make install
```

