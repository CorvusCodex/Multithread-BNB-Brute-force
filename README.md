<p align="left">
  <img src="https://github.com/CorvusCodex/Multithread-BNB-Brute-force/blob/main/Muti%20thread%20bnb%20brute%20force.png">
</p>


# Multithread BNB Brute force

BNB Bruteforce Node.js script that uses the cluster module to create multiple worker processes to generate random BNB keypairs and check if the public address corresponding to the private key is in a Set of full addresses from data.txt. If a match is found, private key and address will be saved inside match.txt

## For people without technical experience you can buy the compiled application for windows from here:
https://ko-fi.com/s/5b402b2757

Keep in mind that a Windows app won’t speed up searching or guarantee success.

## Installation

1. Install Node.js on your system.
2. Clone this repository or download the script.
3. Open a terminal or command prompt and navigate to the directory where the script is located.
4. Run npm install to install the required dependencies.

## Usage

1. Edit file data.txt in the same directory as the script and add the BNB addresses you want to search for, one per line start with 0x. (Like 3 exmples included)
2. Run node app.js to start the script.
3. The script will display the loop count and keys generated per minute for each worker process.
4. The Script look for a FULL address from data.txt
5. If a match is found, the script will save the wallet and its private key (seed) to a file named match.txt and exit.

## Dependencies
This script uses the following dependencies:

1. cluster: Node.js module to create multiple worker processes
2. fs: Node.js module to read and write files
3. os: Node.js module to get system information
4. blessed: A library for creating terminal-based user interfaces
5. ethers: A library for interacting with the Ethereum blockchain

## Support my work for month or year so i can continue to work on my projects:
https://www.buymeacoffee.com/corvuscodex/membership

## Disclaimer

The code within this repository comes with no guarantee, the use of this code is your responsibility. I take NO responsibility and/or liability for how you choose to use any of the source code available here. By using any of the files available in this repository, you understand that you are AGREEING TO USE AT YOUR OWN RISK. Once again, ALL files available here are for EDUCATION and/or RESEARCH purposes ONLY. The chances of finding a match are extremely low and it is not recommended to use this script for any illegal or unethical activities.


## MIT License

Copyright (c) 2025 CorvusCodex

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

