# cloudshell-raid1-lcd
Customised display for ODROID Cloudshell 2 LCD showing RAID-1 Status and system info

Based on the awesome work by https://forum.odroid.com/memberlist.php?mode=viewprofile&u=26989 as detailed here: https://forum.odroid.com/viewtopic.php?f=147&t=29298#p209432

## Instructions

1) First follow these steps: 

https://wiki.odroid.com/accessory/add-on_boards/xu4_cloudshell2/data_recovery#how_to_check_your_disk_failed

2) Replace /bin/cloudshell-lcd with the version in this rep

### Todo

* Check re: failure statuses - did I bungle the output by overriding a varible there? 
* [DONE] Have it display if rclone (rclone.org) is syncing remote data to cloudshell
