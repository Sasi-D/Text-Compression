# Text-Compression
This is the implementation of huffmann coding to compress the static text files.

To execute follow the commands in terminal(both linux and windows do note that you need to have c++ compiler installed(g++)) :

### For Compression
for compressing inputFile.txt use the commands:

    $ g++ encode.cpp sourceCode.cpp -o main
    $ ./main inputFile.txt compressedFile.huf

The required compressed file is stored in compressedFile.huf.

### For Decompression
for decompressing the compressedFile.huf use the commands:

    $ g++ decode.cpp sourceCode.cpp -o main
    $ ./main compressedFile.huf outputFile.txt

The required uncompressed file is stored in outputFile.txt
