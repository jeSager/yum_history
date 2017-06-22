# YUM HISTORY README

### tachyon.cse.sc.edu
#### /home/jason/Desktop/yum_history/README.md


## KERNEL PANIC

* Linux Firewall:  `/etc/selinux/config`
  - added:   `SELINUX=enforcing`

* GRUB, added `selinux=0` on each line



## GRUB FILES

* The file `grub.conf` is a copy of the current config
  - Menu options to boot from each installed kernel were added

* The file `grub.conf.old` was an initial attempt and includes a no-longer installed kernel

* The file `kernel_versions.txt` is the output of `rpm -qa kernel`




## HISTORY FILES

* The file `complete_history.txt` is the result of `yum history list all`

* Other files are the result of `yum history info [ transaction id ]`
  - These files were gathered until a non-system transaction was listed
  - **NOTE:  TRANSACTION ID 101 HAS A FAILING RETURN CODE**
    + _This was the last system change at 6:31pm on the 12th_
  - **NOTE:  TRANSACTION ID 93 WAS ABORTED**
    + _This was the last user change at 3:04pm on May 26_


## UNDO FILES

* These files show the output of the cooresponding rollback commands
  - `yum history undo 101`
  - `yum history rollback 92`


