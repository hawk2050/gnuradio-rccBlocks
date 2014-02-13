gnuradio-rccBlocks
==================

CMake based project for GNU Radio (v3.6 <= x < v3.7) custom signal processing blocks, including a multipath rayleigh fading simulator.

Build instructions:

    mkdir build
    cd build
    cmake ../
    make
    sudo make install
    sudo ldconfig

Build instructions for E100 USRP:

    mkdir build
    cd build
    cmake -DCMAKE_TOOLCHAIN_FILE=../arm_cortex_a8_native.cmake ../
    make
    sudo make install
    sudo ldconfig

