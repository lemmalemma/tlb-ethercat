# TLB-EtherCAT
Custom TLB EtherCAT ESI files.

These files are modifications of the ESI files available from [Laumas](https://www.laumas.com/en/download/).

The base files just have the PDOs set up as a bunch of bytes.

The files here are setup with the actual names of the I/O points.
!(/images/TLB_PDO.png)

There are 2 modified ESI files in this repo. One is for the single channel TLBEtherCAT that assumes the default usage of the unit. The other is for the four channel TLB4EtherCAT that assumes the unit has been changed to operate in 32-bit raw data mode (by sending command 25 to the unit).
