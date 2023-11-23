# aoc-template-python

This is a skeleton for [Advent Of Code](https://adventofcode.com/)

## Language

Python 3

## Usage

### Start

```
./run.sh [DAY]
```

e.g.

```
./run.sh 1 # runs day 01
```

### Implementation

A skeleton for each day is part of this repo.
You have to implement the following functions:

- convert: Receives a string array as input, which contains the lines of the input file. The return can be arbitrary. The result is stored as `self.data`
- run1: Should contain the code for part 1 of the day. Must return the result of this part as string or int
- run2: see run1

With `use_dummy` you can control whether you use the dummy data or the given input data (see below).

## Input

The input data must be placed inside the ``res` folder.
There is a file for example data (`dummy.txt`) and the given input data (`input.txt`)

## Tests

Run all tests:

```
./test.sh
```

## Util/Common

Util and common contain useful functions or classes, which are needed often for AOC, e.g. a 2 dimensional board or and Dijkstra algorithm.

## Hints

The puzzle input of each day is given to the `convert` - function of the day.
The result of the `convert` - function is available as self.data.