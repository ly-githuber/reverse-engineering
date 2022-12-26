# ida arm sig

https://github.com/IridiumXOR/uclibc-sig
uclibc-sig
IDA multiarch SIG files for uClibc library.

The signatures are generated with IDA Flair 7.1 on uClibc 0.9.30.1.

As well explained in MIRAI source code, uClibc 0.9.30.1 was released with a series of precompiled build environment for different CPU architecture (as x86, MIPS, ARM...). This fact has pushed the Linux IoT malware devs, for the sake of simplicity, to use this particular version of uClibc as static library in their samples.

These signatures permits to recognize library functions inside stripped binaries (in general IoT MIRAI based malwares) making reverse engineering job more easy.

For example: this is the representation of the content of a x86-64 GafGyt stripped sample before the application of the signatures:

# another way: use Fire Eye’s IDB2PAT tool on pre-compiled libraries
https://resolverblog.blogspot.com/2019/03/cr1pt0r-ransomware-fireeye-flare.html

# build on your own: IDA FLIRT SIGNATURES FOR LINUX BINARIES
https://www.boozallen.com/insights/cyber/tech/ida-flirt-signatures-for-linux-binaries.html
