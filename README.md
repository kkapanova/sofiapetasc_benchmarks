# Sofiapetasc Benchmarks

This repository consists the following benchmarks for the purposes of SOFIAPETASC Tender

The instructions are primarility based on the [Unified European Applications Benchmark Suite](https://repository.prace-ri.eu/git/UEABS/ueabs/)

- [GROMACS](#gromacs)
- [NAMD](#namd)
- [Quantum Espresso](quantesp)
- [ALYA](#alya)
- [SPECFEM3D](#SPECFEM3D)

Within document [D7.5 Evaluation of Accelerated and Non-accelerated Benchmarks](https://prace-ri.eu/wp-content/uploads/5IP-D7.5.pdf) by PRACE-5IP ,PRACE Fifth Implementation Phase Project a large variety of test cases and information can be found to help with the benchmarks.

## Test Cases
Every benchmark application code within the Unified European Applications Benchmark Suit ha seither one or two input files. In a presence of two input files, Test Case A is specifically created to run on Tier-1 systems (with a little bit over 1000 x86 cores), while Test Case B is created for benchmarking Tier-0 systems (with over 10000 x86 cores). When only test case A is present, then it is suitable for both Tier-1 and Tier-0 systems.

## Application Versions
It is allowed to use newer versions of the applications, if such have become available during the process.

# Metrics
| Application Benchmark  | | Metric  | 
|---|---|---|

| ALYA | |	seconds (-) |
| NAMD | |	seconds (-) |
| GROMACS | | ns/day (+) |
| Quantum Espresso | | seconds (-) |
| SPECFEM3D | |	seconds (-) |
