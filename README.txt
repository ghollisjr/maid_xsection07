maid_xsection07 is a MAID2007 sampler.  It needs the JLab build
system, so it should be built on the JLab computer cluster like this:

make && make install

To see usage information, run without any arguments:
maid_xsection07

See example/for an example program that links to it.

Example executable usage:

echo '1.5 1.0 0 0' | maid_xsection07 2.035 2 0 0
