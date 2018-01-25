# coreboot-b75m-d3h
For testing only. Coreboot files for GA-B75M-D3H.
Rev 1.3 uses flash chips MX25L6406E/MX25L6408E.

flashrom output:

$flashrom -p ch341a_spi

$flashrom v0.9.9-r1954 on Linux 4.13.0-amd64 (x86_64)
flashrom is free software, get the source code at https://flashrom.org

Calibrating delay loop... OK.      
Found Macronix flash chip "MX25L6405" (8192 kB, SPI) on ch341a_spi.      
Found Macronix flash chip "MX25L6405D" (8192 kB, SPI) on ch341a_spi.      
Found Macronix flash chip "MX25L6406E/MX25L6408E" (8192 kB, SPI) on ch341a_spi.      
Found Macronix flash chip "MX25L6436E/MX25L6445E/MX25L6465E/MX25L6473E" (8192 kB, SPI) on ch341a_spi.      
Multiple flash chip definitions match the detected chip(s): "MX25L6405", "MX25L6405D", "MX25L6406E/MX25L6408E", "MX25L6436E/MX25L6445E/MX25L6465E/MX25L6473E"
Please specify which chip definition to use with the -c <chipname> option.
