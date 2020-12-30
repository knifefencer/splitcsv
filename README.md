# splitcsv

Split a CSV file into pieces.

    cat FILE | ./splitcsv  [OPTION]... [- [PREFIX]]    
    
    Output pieces of FILE to PREFIX00, PREFIX01, ...; default size is 1000 lines, and default PREFIX is 'x'.
    
    Read standard input.
    
    params:
        --copy-header
            copy header to each output file
            
        -l N
            put NUMBER lines/records per output 
            
        -a N
            generate suffixes of length N (default 2)

       --additional-suffix=SUFFIX
            append an additional SUFFIX to file names
            
       --help
           display this help and exit
           
       --version
           output version information and exit