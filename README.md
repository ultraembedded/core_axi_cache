### AXI Cache (32-bit input, 256-bit output)

Github:   [https://github.com/ultraembedded/core_axi_cache](https://github.com/ultraembedded/core_axi_cache)

#### Features
* This cache instance is 2 way set associative.
* The total size of 128KB.
* The replacement policy is a limited pseudo-random scheme (between lines, toggling on line thrashing).
* The cache is a write-back cache, with allocate on read and write.
* 32-byte lines
* 32-bit AXI4 input, 256-bit AXI4 output.
* Does not support narrow bursts (Axsize != 2).

