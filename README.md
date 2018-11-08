# M8_Reader
M8_Reader is a set of python scripts for analyzing .m8 files produced by many protein alignment programs (such as DIAMOND). 

## How do I see which files had matches to my proteins?
python3 m8_hits.py -i folder/containing/m8files/ -o my_results.csv

## How do I look at the mutation rates of my proteins across all .m8 files?
python3 m8_stats.py -i folder/containing/m8files/ -o output/folder/
