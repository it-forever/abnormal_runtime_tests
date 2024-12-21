Run firecracker microvm

````
/usr/bin/firectl --firecracker-binary=/usr/bin/firecracker \
--kernel=/media/kernel-lz4-unsec/vmlinux \
--tap-device=tap1/C8:69:C4:2F:CA:10 \
--memory=63488 \
--ncpus=20 \
--socket-path=/tmp/fc-test1.socket \
--kernel-opts="ro console=ttyS0 reboot=k panic=1 pci=off nomodules random.trust_cpu=on ip=192.168.51.30::192.168.51.1:255.255.225.0:::eth0:off" \
--root-drive=/data2/firecracker_data/filesystems/fc-test1/fc-test1-disk1.ext4:rw
````


