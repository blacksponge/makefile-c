# makefile-c

Basic makefile that compile and run C sources.

## Configuration 
Compilers options
* `CC` compiler command (default to `gcc`)
* `CGLAFS` flags that need to be append to the compiler command (default to `-Wall -lm`)
* `PROG` the name of the executable that will be produced (default to `ilikeponies`)

Directories options
* `BUILDDIR` temporary files required for building the executable, basically all *.o and *.d (default to `./build`)
* `BINDIR` the executable will be created here (default to `./bin`)
* `SAVEDIR` all the backups are saved in this one (default to `./backup`)
* `SRCDIR` the directory that contains all your source files (default to `./src`)
* `DOCDIR` finally the directory that will contain the documentation (default to `./doc`)

Documentation options
* `DOXYFILE` path to the Doxgen configuration file

## Utilization
TODO
