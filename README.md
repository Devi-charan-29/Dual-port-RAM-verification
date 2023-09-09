# Dual-port-RAM-verification
Dual Port Ram (DPRAM) is a type of random-access memory that allows multiple reads or writes to occur at the same time,unlike single-ported RAM which allows only one access at a time.

It is a memory accessed by two set of address,data and control signals

####Specifications:
1. Clock(clk) is for synchronizing all the read and write operations.
2. Reset(rst) will clear all the locations in the memory.
3. wr,w_addr,w_data are the signals corresponding to write operation.
4. rd,r_addr,r_data are the signals corresponding to read operation.

#### Readduring write behaviour 
During a write, newdata appears at the output of the written port (w_data) of the Dual port RAM block. If a read operation occurs simultaneously at the same address as  a write operation, old data appears at the read output port (r_data).

![block-ram-dual-port](https://github.com/Devi-charan-29/Dual-port-RAM-verification/assets/95524221/15e1542e-8e81-4a8a-9fc0-3c79ec51b5e4)

###Test bench Architecture

![Screenshot (251)](https://github.com/Devi-charan-29/Dual-port-RAM-verification/assets/95524221/b28a7e79-2677-4247-b70f-0ee7d4d9ebb9)




