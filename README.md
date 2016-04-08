#nesasm

Fork of nesasm v3.1: [http://www.nespowerpak.com/nesasm/](http://www.nespowerpak.com/nesasm/)

##Installation

```
make && sudo make install
```

##Usage

```
NES Assembler (v3.2)

nesasm [-options] [-? (for help)] infile

-s/S     : show segment usage
-l #     : listing file output level (0-3)
-m       : force macro expansion in listing
-f       : output fns
-raw     : prevent adding a ROM header
-t <bin> : trainer binary
-srec    : create a Motorola S-record file
infile   : file to be assembled
```

##Updates

* Updated usage.txt
* Updated Makefile
* Updated max label/line sizes
* Added flag for .fns output
* Added trailer support
* Cleaned up code (removed errors/warnings)

See commit history for exact change details