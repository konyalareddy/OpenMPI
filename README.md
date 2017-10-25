# openMPI
This includes how to install the toolchain and sample program for parallel processing
I have installed on Ubuntu 17.xx, 
1. Download openmpi-X.X.X.tar.gz form openmpi.org
2. Unzip the file using following command
    tar -xvf openmpi-3.0.0.tar.gz 
3. Goto the directory
     cd openmpi-3.0.0
4. Creaete a build directory
    mkdir build
5. Goto build dirctory
    cd build/
6. Configure the system using following command
    ../configure 
7. Give teh following command for building mpicc, this will take some time.
    make  all install
 give the command mpicc, if some shared libraries are not found, give the command 
    ldconfig
