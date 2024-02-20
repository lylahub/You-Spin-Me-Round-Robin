# You Spin Me Round Robin

Writing the implementation for round robin scheduling for a given workload and quantum 
    length given a basic skeleton that parses an input file and command line arguments.

## Building

```shell
make
```

## Running

cmd for running
```shell
./rr your_processes_file.txt [int]
```

```shell
./rr processes.txt 3
```

Results: when quantum length = 3:

```shell
./rr processes.txt 3
Average waiting time: 7.00
Average response time: 2.75
```


## Cleaning up

```shell
make clean
```