# Samba file share

## Formatteer openstack volume

Indien vers (nog ongebruikt) openstack volume moet de schijf eerst geformatteerd worden.

Op de Linux samba server machine:

```
# TODO: uitwerken
# dingen met 'fdisk -l' en 'mkfs.ext4'
```

zie: (o.a.) <https://www.tecmint.com/add-new-disk-to-an-existing-linux/>

## Mount openstack volume

```
sudo mkdir /mnt/store
sudo mount /dev/sdb /mnt/store
```