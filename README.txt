Usage:
1. Have an implementation of IReadFIFO and IWriteFIFO for the bit file containing a FPGAHealthAndStatus module.
2. Use the setReadFIFO.vi and setWriteFIFO.vi to configure the RTHealthAndStatus.lvclass with its correct interfaces.
3. Use clearHealthAndStatus.vi, receiveAllHealthAndStatus.vi, and receiveHealthAndStatus.vi to manipulate the health and status data on the FPGA.