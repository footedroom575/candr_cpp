# CANDR - Compile And Run

CANDR is a very basic **Linux shell script** to compile and execute C++ (.cpp) files.

It executes the CPP Program immediately if it gets compiled successfully. Otherwise, it shows the output or the compilation error.

## Installation:

Download this utility first.

Using Git:

`git clone https://github.com/footedroom575/candr_cpp.git`

or download as zip from **"Code"** -> **"Download ZIP"** option above.

Extract the zip and run the following in the candr_cpp folder:

`sudo bash ./install.sh`


## Usage:

Run this command in the working directory where (.cpp) file is stored.

`candr filename`

It will execute the file as `g++ filename.cpp -o filename`
And will later execute it as `./filename`

**Note**: Don't add .cpp at the end of the filename, it does this work for you :)