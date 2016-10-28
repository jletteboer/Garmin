# garmin-connect-tcx2csv

## Description 
This script is parsing Garmin Connect tcx files downloaded with the script ```gcexport.py``` from [Kyle Krafka](https://github.com/kjkjava/garmin-connect-export) to a custom formatted csv file.

## Usage
There are usage detail from the ```--help``` flag:

```
usage: tcx2csv.py [-h] [-f [{tcx}]] [-i [INPUT]] [-o [OUTPUT]]

optional arguments:
  -h, --help            show this help message and exit
  -f [{tcx}], --format [{tcx}]
                        export format; can be only 'tcx' (default: 'tcx')
  -i [INPUT], --input [INPUT]
                        the directory to import to (default: '.')
  -o [OUTPUT], --output [OUTPUT]
                        the directory to export to (default: '.')
```

