# lspy

A quick script to list the names exported by a python module

```console
$ lspy -h
usage: lspy [-h] [-p] [-m] [-a] [-g] module

List the names exported by a python module

positional arguments:
  module         module to import

  optional arguments:
    -h, --help     show this help message and exit
    -p, --private  include private names
    -m, --magic    include magic names
    -a, --all      include all names (equivalent to `-pm')
    -g, --grep     print modules as grep expression instead of one per line
```
