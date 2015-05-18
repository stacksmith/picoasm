This is picoasm from http://www.xs4all.nl/~marksix/picoasm.html.

Several modifications were made:

1) <string.h> included where needed in order to compile;
2) modified to output .mem file (for bitstream insertion) as described in http://www.labbookpages.co.uk/fpgas/picoBlaze.html
3) Makefile modified to link statically, as xilinx toolpath interferes with library loads.