# minix-by-Jean-Loups-White
Official MINIX sources - Automatically replicated from gerrit.minix3.org

![My Dream of MINIX](images/MyDream.png)

I try te develop Minix 3 on --> https://www.beagleboard.org/boards/beaglebone-ai-64

### Cross compile on Ubuntu 23.04 LTS

#### Install dependencies

Before attempting to cross-compile MINIX, you need a working C toolchain, Git and some additional software on your host platform.

For Debian-based operating systems, run the following command as super-user:

$ sudo apt-get install build-essential curl git libc6 zlib1g zlib1g-dev

Note: Also on Ubuntu, if you get an error stating that “'/lib/cpp' fails sanity check”, you need to install the GNU C++ compiler:

$ sudo apt-get install g++

Note: On FreeBSD and Minix (compiling for ARM on x86, e.g.), if you get a message along the lines of “Skipping image creation: missing tool 'mcopy'”, please install the emulators/mtools package.

