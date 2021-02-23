This folder contains data for the three task graph applications. The format of each set of data is as follows:

10 3 58// number of tasks, number of processors, FPGA resource limit

-1 -1 -1 -1 21 -1 -1 -1 -1 -1 //task graph
-1 -1 -1 -1 -1 11 -1 -1 -1 -1 
-1 -1 -1 20 18 15 -1 -1 -1 -1 
-1 -1 -1 -1 -1 -1 -1 18 -1 -1 
-1 -1 -1 -1 -1 -1 17 -1 -1 -1 
-1 -1 -1 -1 -1 -1 19 8 -1 -1 
-1 -1 -1 -1 -1 -1 -1 -1 10 -1 
-1 -1 -1 -1 -1 -1 -1 -1 10 19 
-1 -1 -1 -1 -1 -1 -1 -1 -1 -1 
-1 -1 -1 -1 -1 -1 -1 -1 -1 -1 

27.0 18.0 24.0 12.0 //tasks on m processors and FPGA
15.0 15.0 16.0 10.0 
22.0 27.0 24.0 14.0 
15.0 18.0 12.0 8.0 
23.0 22.0 22.0 14.0 
20.0 15.0 17.0 10.0 
18.0 24.0 25.0 12.0 
22.0 18.0 22.0 12.0 
21.0 18.0 19.0 12.0 
20.0 19.0 22.0 12.0 

0.00 1.23 0.69 0.88 //communication access cost between computing units
1.23 0.00 1.20 1.36 
0.69 1.20 0.00 1.06 
0.88 1.36 1.06 0.00 

0.0 2.0 2.0 3.0 //communication rate between computing units
2.0 0.0 3.0 3.0 
2.0 3.0 0.0 3.0 
3.0 3.0 3.0 0.0 

24 20 28 16 28 20 24 24 24 24 //FPGA resource required of each task
