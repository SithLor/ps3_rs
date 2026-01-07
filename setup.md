# help stuuf

https://www.bucanero.com.ar/2019/08/14/building-your-ps3-dev-environment-on-macos/

sudo apt-get install autoconf automake bison flex gcc libelf-dev make \
    texinfo libncurses5-dev patch python3 subversion wget zlib1g-dev \
    libtool libtool-bin python3-dev bzip2 libgmp3-dev pkg-config g++ libssl-dev clang
sudo apt install nvidia-cg-toolkit python2

install  https://github.com/bucanero/ps3toolchain to /usr/local/ps3dev

ls -la /usr/lib/x86_64-linux-gnu/libcrypto.so*
wget http://archive.ubuntu.com/ubuntu/pool/main/o/openssl/libssl1.1_1.1.1f-1ubuntu2_amd64.deb
sudo dpkg -i libssl1.1_1.1.1f-1ubuntu2_amd64.deb



















git clone https://github.com/ps3dev/ps3toolchain
git clone https://github.com/ps3dev/PSL1GHT
git clone https://github.com/ps3dev/ps3libraries

sudo apt-get install autoconf automake bison flex gcc libelf-dev make \
    texinfo libncurses5-dev patch python3 subversion wget zlib1g-dev \
    libtool libtool-bin python3-dev bzip2 libgmp3-dev pkg-config g++ libssl-dev clang
sudo apt install nvidia-cg-toolkit
