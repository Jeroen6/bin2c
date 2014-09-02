# Usage

    bin2c [OPTION...] FILE [FILE...]

    Options:
      -d, --header <file name>  Name a header file (A header file will not be created  unless explicitly named)
      -h, --help                Print a command line help and exit immediately
      -o, --output <file name>  Name an output file
      -m, --macro               Create the size definition as a macro instead of a const
      -n, --name <symbol name>  Name the symbol to be defined
      -v, --version             Print version information and exit immediately

    Examples:
      bin2c -o foo.h bar.bin
            Create 'foo.h' from the contents of 'bar.bin'

      bin2c -o foo.h file1 file2
            Create 'foo.h' from the contents of 'file1' and 'file2'

      bin2c -d foo.h -o foo.c bar.bin
            Create 'foo.c' and 'foo.h' from the contents of 'bar.bin'
