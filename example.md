Ostap installation guide for CERN SWAN service
==============================================
To install the Ostap project on the CERN SWAN service, you must perform the following steps:

1. Run a local session in [CERN SWAN](http://swan.cern.ch/)
2. Go to the terminal and clone the latest released version and build Ostap package
    
    git clone —-branch <latest tag> git://github.com/OstapHEP/ostap.git
    cd ostap
    mkdir build
    cd build
    cmake .. -DCMAKE_INSTALL_PREFIX=<INSTALL_DIRECTORY>
    make -j8
    make install
    source <INSTALL_DIRECTORY>/thisostap.sh 
For the latest tag check the page https://github.com/OstapHEP/ostap/releases
![Image Terminal](https://github.com/Pro100Tema/SWAN_Image/blob/master/terminal.jpg)

3.
