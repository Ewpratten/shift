# shift
Keyed text encoding

## Installation
To install shift, run the following:
```sh
git clone https://github.com/ewpratten/shift.git
cd shift
mkdir build && cd build
cmake ..
make
```

The shift executable will be built at `./`

## Speed
By using Python's `cProfile` tool, we can see the time required to encode and decode `example.txt`. This file contains 50 paragraphs generated by [lipsum.com](https://www.lipsum.com), using the key `ewpratten`:
```
Encoding:  0.070 seconds 
Deconding: 0.062 seconds
```
