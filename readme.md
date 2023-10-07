Various machine code utilities

HEXLD3 - a program from the brilliant book: "Matsering Machine Code on your ZX Spectrum". 
This allows you to:
1) List machine code
2) write it in HEX
3) run it
4) delete it
3) insert code
4) copy code
and a few otgher, check book for details (its available at archive.org)

HEXLD3_V3 is the latest and has a better list (run 10); however, this has broken breakpoint as
the addition to list overwrote the first two bytes of BREAKPT 0xff2a. This should be fixable.
The improvement to list is to list 8 bytes per line.