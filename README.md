VirtualBox is a free and open-source virtualization software that allows you to run multiple operating systems on a single physical machine. Installing it involves the following steps:
1.	Download: Go to the official VirtualBox website and download the version compatible with your operating system (Windows, macOS, Linux).
2.	Run Installer: Open the downloaded file and follow the installation wizard. You can choose default settings or customize features like network options.
3.	Network & Permissions: During installation, you may need to approve network interface and driver installations. On macOS, grant system permissions if prompted.
4.	Complete Installation: Finish the wizard and launch VirtualBox. You can now create virtual machines to install other operating systems.

1 Yosys on Ubuntu:
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make
$ sudo apt-get install build-essential clang bison flex \ libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev \ libboost-python-dev libboost-filesystem-dev zlib1g-dev 
$ make config-gcc 
$ make 
$ sudo make install     

2 iyerilog on Ubuntu:
verilog Steps to install iverilog
 sudo apt-get update 
sudo apt-get install iverilog

3.gtkwave on Uuntu
sudo apt-get update 
sudo apt install gtkwave
