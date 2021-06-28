# Harddrive

## Lister les disques, trouver les modèles

```
lshw -C disk
  *-disk:0
       description: ATA Disk
       product: Samsung SSD 850
       physical id: 0
       bus info: scsi@0:0.0.0
       logical name: /dev/sda
       version: 2B6Q
       serial: S2RBNX0K125517R
       size: 465GiB (500GB)
       capabilities: gpt-1.00 partitioned partitioned:gpt
       configuration: ansiversion=5 guid=edc6bdc3-0fef-4e3b-a3c1-74dae90aee17 logicalsectorsize=512 sectorsize=512
  *-disk:1
       description: ATA Disk
       product: Samsung SSD 850
       physical id: 1
       bus info: scsi@1:0.0.0
       logical name: /dev/sdb
       version: 2B6Q
       serial: S2RBNX0K125505M
       size: 465GiB (500GB)
       capabilities: gpt-1.00 partitioned partitioned:gpt
       configuration: ansiversion=5 guid=bee8f500-f26d-4bac-80f1-6eae09ed06fa logicalsectorsize=512 sectorsize=512
```


```
$ udisksctl status
MODEL                     REVISION  SERIAL               DEVICE
--------------------------------------------------------------------------
Samsung SSD 850           2B6Q      S2RBNX0K125517R      sda
Samsung SSD 850           2B6Q      S2RBNX0K125505M      sdb
```
