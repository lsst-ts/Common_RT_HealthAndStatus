Usage:
1. Have an implementation of IReadU32FIFO and IWriteU64FIFO for the bit file containing a FPGAHealthAndStatus module.
2. Use the setCommandFIFO.vi and setResponseFIFO.vi to configure the RTHealthAndStatus.lvclass with its correct interfaces.
3. Use clearHealthAndStatus.vi, receiveAllHealthAndStatus.vi, and receiveHealthAndStatus.vi to manipulate the health and status data on the FPGA.