PyBuildTool C Sample
====================

Installation Instruction for Ubuntu
-----------------------------------

* sudo apt-get install cppcheck
* sudo apt-get install splint
* sudo apt-get install doxygen
* sudo apt-get install python-virtualenv


Using
-----

1. git clone https://github.com/dozymoe/pybuildtool-c-sample
2. cd pybuildtool-c-sample
3. git submodule update --init --recursive
4. ./setup.sh
5. ./build.sh
6. ./watch.sh


Notes
-----

* if `splint` couldn't find "sys/types.h" see:
  [where's my usr/include/sys directory](http://askubuntu.com/questions/414110/wheres-my-usr-include-sys-directory)
