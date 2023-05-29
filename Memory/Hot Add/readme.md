# KVM
This is the same as "Ballooning" but has to be done manually. Todo: Build a monitoring utility that sends signals from the guest to host to increase automatically!

## set manually:
```virsh setmem $VM 2G```

sch: https://www.google.com/search?q=kvm+hot+add+memory
- https://www.unixarena.com/2015/12/linux-kvm-how-to-add-remove-memory-to-guest-on-fly.html/

## grow automatically
https://pmhahn.github.io/virtio-balloon/
>Automatic Ballooning
>Currently (2019-05) that ballooning has to be done manually with Qemu. There was a project from 2013 to implement automatic >ballooning, but it was never completed.


# Xen

# containers
