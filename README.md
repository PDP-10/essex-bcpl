# essex-bcpl
Essex BCPL for TOPS-10

Essex BCPL is the Esssex University DEC PDP-10 TOPS-10 implementation of BCPL. This is required in order to compile MUD1 from
source.

COMPIL.MAC is a revised source of the DEC issued COMPILE command for DEC PDP-10 TOPS-10 Monitor 7.04 so that it recognises the BCPL file
type for compilation, linking and executing. This should be compiled using EXECUTE COMPIL.MAC/SSAVE and put the EXE in the SYS: library
if you intend to regularly use BCPL.

A SIMH TOPS-10 tape containing the BCPL COMPIL.EXE is in bcplcompil.tap. Restore to SYS: [1,4]

More detailed instructions for installation at https://www.quentin.org.uk/2018/02/25/installing-bcpl/
