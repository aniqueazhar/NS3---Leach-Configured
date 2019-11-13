# Supported Operating System:
Linux 12.02 LTS

Update the gcc compiler to 5.4 version

Pull and extract the code in your /home directory

Firstly, build the code by using ./build.py command in ns-allinone-2.27

After successfull build use ./waf script for command execution

# leach_ns3- Configured:
Gcc version -- 5.4
Python Version -- 2.7

## TO Build:

./waf clean
./waf configure
./waf build

# To Execute LEACH:
All LEACH protocol and its supported files are located in /ns-3.27/scratch folder

For suuccessful execution of LEACH protocol use following commands

./waf --run test
./waf --run leach
