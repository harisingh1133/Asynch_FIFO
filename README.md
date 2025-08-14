# Asynch_FIFO
Dual clock Asynchronous FIFO Implementation in Verilog.
To avoid the metatstability and data errors when transfering the  data from one clk domain to another clk domain, we use Asynchronous FIFO.
This module is verified by giving two clk frequencies , write_clk at 50MHz and read_clk at 25Mhz.
Used the Gray code counter to synchronize the two clk domains.
