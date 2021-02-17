# evermos-be-assesment

Task 1: Online Store

1. This condition occurs because of the racecondition, namely two or more of the same processes running at almost the same time. For example, the checkout process is carried out simultaneously by the user which causes the stock of goods to be invalid because the other stock reduction process is still running.


2. My solution to this case is to use Redis: Real-Time Inventory Management. So using storage in memory will speed up the transaction of stock items so that when there is a process that simultaneously accesses the same endpoint there will be no racecondition.