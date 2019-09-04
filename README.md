OutGuess is a universal steganographic tool that allows the insertion of hidden information into the redundant bits of data sources. 

http://web.archive.org/web/20150419030527/http://www.outguess.org/

# outguess

This is a copy of the last available source code on the archived website. I installed it from the AUR on Arch but the build is broken. 
Cloning this to my system and running the following command compiled it without issue. There are no manpages supplied with this build.

```
$ ./configure && make
```

```
OutGuess 0.2 Universal Stego (c) 1999-2001 Niels Provos

outguess [options] [<input file> [<output file>]]
        -[sS] <n>    iteration start, capital letter for 2nd dataset
        -[iI] <n>    iteration limit
        -[kK] <key>  key
        -[dD] <name> filename of dataset
        -[eE]        use error correcting encoding
        -p <param>   parameter passed to destination data handler
        -r           retrieve message from data
        -x <n>       number of key derivations to be tried
        -m           mark pixels that have been modified
        -t           collect statistic information
        -F[+-]       turns statistical steganalysis foiling on/off.
                     The default is on.
```



