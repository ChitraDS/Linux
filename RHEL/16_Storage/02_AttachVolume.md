lsblk
fdisk /dev/xvdf
mkfs -t ext4 /dev/xvdf
mkdir /tmp/test
mount /dev/xvdf /tmp/test
