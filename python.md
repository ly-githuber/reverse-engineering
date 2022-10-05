decompiling python 3.10 .pyc

download code from:
https://github.com/zrax/pycdc

from your directory where the cmakelist.txt exists. here are steps:

mkdir build
cd build
depending upon the architecture you're using
    cmake -G "Visual Studio 16 2019" -A x64 ../"
    
then go to VS2019 and build the binaries, then run the pycdc.exe with given .pyc
