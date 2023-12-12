# EBS Volume
<br>
***********
<br>
EBS volumes
<br>
***********
<br>
> Create a volume
<br>
> Attach it to a EC2 instance
<br>
> Connect to the EC2 instance
<br>
> Take control
<br>
> Check whether volume is attached
<br>
# lsblk
<br>
> Chek if there is any data on volume
<br>
# file -s /dev/xvdf
<br>
> Create a file system for volume
<br>
# mkfs -t ext4 /dev/xvdf
<br>
# mkdir /fileserver
<br>
# mount /dev/xvdf /fileserver
<br>
# cd /fileserver
<br>
> Create some files using nano
<br>
> Unmount the volume 
<br>
# umount /dev/xvdf
<br>
> Check whether volume is unmounted or not
<br>
# cd /fileserver
<br>
# ls 
