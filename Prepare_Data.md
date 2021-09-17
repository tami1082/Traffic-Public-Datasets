**This file amis to describe data processing code, including data formate, code strcuture and final train/val/test data.**  
There are two data prcocessing codes coming from  **[ASTGCN](https://github.com/guoshnBJTU/ASTGCN-r-pytorch) & [DCRNN](https://github.com/liyaguang/DCRNN)**. 

* 1.ASTGCN  
In PEMS04, raw data's size is (16992,307,3). you can change the number of week/day/hour in XX.conf file. The number of week means how many weeks are choosen, similar with the number of day/hour. For example, if you set the number of week = 1 (other number can also be chosen), the whole process can be presented by the below pic.  
