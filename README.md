# burnit 🔥🔥

 A simple CPU stress tester.

## Compilation and execution

On windows the command prompt script can be used to compile and execute the programed with the default settings.
After that the executable can be run with different settings using the flags listed below.
If not on windows you can follow the compilation outline in the command prompt script.
Must be compiled with `-std=c++17`

## Flags

```
[-t,--threads threads] [-s,--seconds seconds] [-l,--limit limit] [-k,-keepgoing] [-h] 
```

- `-t,--threads threads`
    - Allows you to adjust the number of threads used which in turn adjusts the number of CPU cores
    - The default value is determined by the system core count (including multi-core systems)

- `-s,--seconds seconds`
    - Allows you to adjust the number of seconds the stress tester is run
    - The default value is 5 seconds
- `-l,--limit limit`
    - Allow you to adjust the upper limit when searching for primes
    - The default value is 10'000'000
- `-k,-keepgoing`
    - Overrides the default seconds value and allows for infinite execution time
    - The default value is false

## Credit
A large portion of the source code was written by Pol Marcet and was contributed to:
Primes Benchmark (c) 2021 Dave's Garage - http://github.com/davepl/primes