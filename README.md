# YUM HISTORY README

### tachyon.cse.sc.edu
#### /home/jason/Desktop/yum_history/README.md


## GRUB FILES

* The file `grub.conf` is a copy of the current config
  - Menu options to boot from each installed kernel were added

* The file `kernel_versions.txt` is the output of `rpm -qa kernel`



## HISTORY FILES

* The file `complete_history.txt` is the result of `yum history list all`

* Other files are the result of `yum history info [ transaction id ]`
  - These files were gathered until a non-system transaction was listed
  - ** NOTE:  TRANSACTION ID 100 HAS A FAILING RETURN CODE **
    + _This was the last system change at 6:31pm on the 12th_



## THE UNDO FILE

* This file is the output from the command `yum_history_undo_101`


