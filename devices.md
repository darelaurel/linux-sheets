fdisk -l : listing of all devices

mount /dev/sdb1 /media/darel/datas ===> will the device sdb1 in media/darel/datas folder (can be done manually or by OS)

du -a folder : show some stats on folder


mkfs.exfat -n "Disque" /dev/sdb1 ==> will format /sdb1 in NTFS (exFat)

mkfs.vfat -F 32 -n "Disque" /dev/sdb1 ==> will format /sdb1 in FAT32