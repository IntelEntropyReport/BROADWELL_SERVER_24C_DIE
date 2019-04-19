The files here are taken from the entropy source output of the DRNG with no processing appllied.

They are collected at 5C increments from -10C to 110C package temperature.

Each data file is 10 MiBytes long (10485760 Bytes).

The output of the entropy source is bit serial. Data is in little endian format, with the first bit from the entropy source arriving in bit 0 of a byte.

The filenames are formatted to be parsed by djent with the -p option to extract the condition, voltage and temperature from the filename.

Two CSV files are included, with the djent results for 1 bit and 8 bit symbols.

A file -filename.txt- contains a sorted by temperature list of the data filenames.

```
filenames.txt
noxor_1bit_statistics.csv
noxor_8bit_statistics.csv
rawdata_CID-BDX_PROC-noxor_1p0V_0p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_100p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_105p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_10p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_-10p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_110p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_15p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_20p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_25p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_30p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_35p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_40p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_45p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_50p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_55p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_5p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_-5p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_60p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_65p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_70p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_75p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_80p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_85p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_90p0C_.bin
rawdata_CID-BDX_PROC-noxor_1p0V_95p0C_.bin
```

