# CompressXpress

## Overview
CompressXpress is a text file compression and decompression tool implemented in C. This project focuses on achieving high compression ratios without sacrificing data accuracy. It exemplifies the effectiveness of Huffman Coding in minimizing file sizes for storage and transmission, making it a valuable addition to data manipulation tasks. The project centers on the compression and subsequent decompression of text files, involving complex algorithms, data structures, and file manipulation intricacies.

## Features
### 1. High Compression Ratios
CompressXpress is designed to achieve high compression ratios, ensuring efficient use of storage space without compromising data accuracy. The project demonstrates the power of Huffman Coding in reducing file sizes.

### 2. Huffman Coding Implementation
The project showcases the effectiveness of Huffman Coding in text file compression. This compression algorithm is used to encode characters with variable-length codes, with more frequent characters having shorter codes, resulting in optimal compression.

### 3. Data Accuracy Preservation
Despite the focus on compression, CompressXpress prioritizes data accuracy. The decompression process ensures that the original text files are accurately reconstructed, maintaining the integrity of the data.

### 4. Real-world Data Compression Scenarios
The project provides insights into real-world data compression scenarios, addressing the challenges of working with diverse text data and optimizing compression for different use cases.

## Prerequisites
Before using CompressXpress, ensure you have the following installed:
- C compiler (e.g., GCC)
- Make utility

## Installation
1. Clone the repository: `git clone https://github.com/your-username/compressxpress.git`
2. Navigate to the project directory: `cd compressxpress`
3. Compile the source code using the provided Makefile: `make`
4. Run the application: `Run .\aar <parameter> <filename with extension> <br> ; Parameters:<br> ; -e : To encode the file<br>  ;  -d : To decode the file<br>`

## Usage
- To compress a text file, use the command: `./compressxpress -c input.txt output.cpx`
- To decompress a compressed file, use the command: `./compressxpress -d input.cpx output.txt`
- Follow the on-screen prompts for additional options and configurations.

Sit back and witness the magic of CompressXpress as it efficiently compresses and decompresses text files while maintaining high data accuracy.

