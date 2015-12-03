# BandAliginingFromData

Author : keeeto

## About

This code is associated with the paper "Screening procedure for structurally and electronically matched contact layers for high-performance solar cells: hybrid perovskites" and pertains to the first step in the screening process. It is a simple application of Anderson's rule for band alignment.

## Use

The ionisation potential (IP) and electron affinity (EA) data are contained in the text file.

The screening procedure can be performed using the interactive iPython notebook or the standalone python script.

In order to run the exact same screening procedure as performed in the paper one simply execurtes:

``` python python BandAlign.py -i 5.4 -e 4.0 -w 0.8 ```

For extension to other screening one can input the IP `-i` and EA `-e` of the absorber layer of choice along with a window for matching `-w`. The window means that values within +/- 0.5*window are accepted as good electrical contacts.

## References

* Anderson, R. L., (1960). Germanium-gallium arsenide heterojunction, IBM J. Res. Dev. 4(3), pp. 283–287


