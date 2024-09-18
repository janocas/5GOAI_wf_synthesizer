# COMPILE
```
cd cmake_targets
./build_oai -w USRP --gNB
```

# RUN
```
cd ran_build/build
./sudo ./nr-softmodem -O ../../../targets/PROJECTS/GENERIC-NR-5GC/CONF/gnb0.prs.band261.fr2.64PRB.usrpx310.conf --sa --rfsim --rfsimulator.options saviq --rfsimulator.IQfile /tmp/fr2_IQ_2752308.dat 10
```
This command generates 10 frames where MSI is available.

