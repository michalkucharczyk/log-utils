#### Usage
```
# prerequisites:
$ gnuplot --version
gnuplot 5.4 patchlevel 2

# headsup - this creates a `log_file_name` directory:
$ ./parse-log.py log_file_name.log

# generate a png file
$ ./draw-log.py ./log_file_name --graphs txpool_maintain_duration,block_proposing,txpool_maintain
```
