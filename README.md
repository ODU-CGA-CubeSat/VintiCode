# VintiCode

## Build with CMake

```bash
mkdir build
cd build
cmake ..
make
```

## Usage

### Input File

Create `inputStateVect.txt` in `build/` directory, example below (ECI)

```
4063.75
0
5134.54
0
7.826
0
```

### Running

```bash
./VintiCode
```

Outputs new state vector to `outputStateVect.txt` (ECI cartesian and mean elements)

## State Vector Example

The rows in `inputStateVect.txt` and `outputStateVect.txt` correspond to [ECI](https://en.wikipedia.org/wiki/Earth-centered_inertial) state vector which gives position and velocity in cartesian coordinates.
```
x  =      2328.9659400000   km
y  =     -5995.2160000000   km
z  =      1719.9789400000   km
xd =         2.9111011300   km/s
yd =         -.9816405300   km/s
zd =        -7.0904992200   km/s
```
