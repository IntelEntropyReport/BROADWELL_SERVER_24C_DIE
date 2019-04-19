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

This data is valid for the following products:

```
Intel® Xeon® Processor E5-2673 v4
Intel® Xeon® Processor E5-2676 v4
Intel® Xeon® Processor E5-2678 v4
Intel® Xeon® Processor E5-2679 v4
Intel® Xeon® Processor E5-2682 v4
Intel® Xeon® Processor E5-2683 v4
Intel® Xeon® Processor E5-2686 v4
Intel® Xeon® Processor E5-2688 v4
Intel® Xeon® Processor E5-2689A v4
Intel® Xeon® Processor E5-2689 v4
Intel® Xeon® Processor E5-2695 v4
Intel® Xeon® Processor E5-2696 v4
Intel® Xeon® Processor E5-2697A v4
Intel® Xeon® Processor E5-2697R v4
Intel® Xeon® Processor E5-2697 v4
Intel® Xeon® Processor E5-2698B v4
Intel® Xeon® Processor E5-2698R v4
Intel® Xeon® Processor E5-2698 v4
Intel® Xeon® Processor E5-2699A v4
Intel® Xeon® Processor E5-2699C v4
Intel® Xeon® Processor E5-2699R v4
Intel® Xeon® Processor E5-2699 v4
Intel® Xeon® Processor E5-4660 v4
Intel® Xeon® Processor E5-4667 v4
Intel® Xeon® Processor E5-4669 v4
Intel® Xeon® Processor E7-4809 v4
Intel® Xeon® Processor E7-4820 v4
Intel® Xeon® Processor E7-4830 v4
Intel® Xeon® Processor E7-4850 v4
Intel® Xeon® Processor E7-8855 v4
Intel® Xeon® Processor E7-8860 v4
Intel® Xeon® Processor E7-8867 v4
Intel® Xeon® Processor E7-8870 v4
Intel® Xeon® Processor E7-8880 v4
Intel® Xeon® Processor E7-8890 v4
Intel® Xeon® Processor E7-8891 v4
Intel® Xeon® Processor E7-8893 v4
Intel® Xeon® Processor E7-8894 v4
Intel® Xeon® Processor E7-8895 v4
```
