# Text-Compression
This is the implementation of huffmann coding to compress the text files.

To execute the file follow the commands in terminal(both linux and windows do note that you need to have g++ installed) :

for compressing inputFile.txt use the commands:
    g++ encode.cpp sourceCode.cpp -o main
    ./main inputFile.txt compressedFile.huf

The required compressed file is stored in compressedFile.huf file.

for decompressing the compressedFile.huf use the commands:
    g++ decode.cpp sourceCode.cpp -o main
    ./main compressedFile.huf outputFile.txt

The required uncompressed file is stored in outputFile.txt
