# Fast BogoSort in C++

## Project Description

This project is for fun and educational purposes, it is an implementation of the notoriously inefficient BogoSort algorithm in C++. The goal of this project is to demonstrate a multi-threaded version of BogoSort using C++ features. The program utilizes multiple CPU cores to shuffle and sort an array as quickly as possible. The implementation includes a custom pseudo-random number generator (PRNG) based on the xoshiro256++ algorithm for shuffling the array.

## Performance

The performance of this multi-threaded BogoSort implementation can vary depending on the hardware and the number of threads used. In testing, it achieved:

- Up to 5 million iterations per second on a single thread
- Up to 3 million iterations per second per thread when running with 16 threads simultaneously


## Features

- Multi-threaded BogoSort implementation
- Ability to utilize multiple CPU cores for parallel execution
- Performance metrics output, including elapsed time and iterations per second

### Prerequisites

- A C++ compiler that supports C++11 or later

## Example Output

```text
Welcome in "fast" BogoSort in C++
Number of available CPU cores: 8
How many would you like to use? (1-8) ?
4
Write your unsorted array in format: 5 3 7 1 4
5 3 7 1 4
Sorted
Iterations per thread: 172800
Time: 0.2 seconds Iterations per second by successful thread: 864000
```


---

Enjoy sorting with one of the most inefficient algorithms in a fast and multi-threaded way!
