# essex-bcpl
Essex BCPL for TOPS-10

Essex BCPL is the Essusex University DEC PDP-10 TOPS-10 implementation of BCPL. This is required in order to compile MUD1 from
source.

COMPIL.MAC is a revised source of the COMPILE command for DEC PDP-10 TOPS-10 Monitor 7.04 so that it recognises the BCPL file type
for compilation, linking and executing. This should be compiled using COMPIL COMPIL.MAC/COMPILE and put in the SYS: library
if you intend to regularly use BCPL.
