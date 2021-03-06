# Complex Number
> Implement methods to operate complex numbers.

### Contributors

* Lucas Leandro Costa Lacerda


## Developing

### Built With
 - iostream
 - string
 - cmath

 ## Getting started

To use the Complex class with polar implementation instantiate with the format bellow.
```cpp
Complex c(5, 45)
```
The first parameter is the real number (radius) and the second is the imaginary number (angle in degrees).

To use the Complex class with euclidean implementation instantiate with the format bellow.
```cpp
Complex c(2, 15)
```
The first parameter is the real number (x axis) and the second is the imaginary number (y axis).


### Setting up

Inside the `run.sh` file you can add repositories to use like the example bellow:
```shell
dependencies=("complex-number;https://github.com/LucasLacerdaCL/complex-number.git")
```

Execute the `run.sh` file to generate the binary files inside `dist` folder.

For OSX:
```shell
sh ./run.sh
```

For Windows:
```shell
./run.sh
```

Inside the `bootstrap.sh` file you can inject the dependencies like the example bellow:
```shell
yourBinary="exemple.o"
yourMain="main.o"

imports=("complex-number;complex.euclidean.o")

cmdLine="./${yourBinary} ./${yourMain}"
```

Execute the `bootstrap.sh` file to generate the `main.exe` file.

For OSX:
```shell
sh ./bootstrap.sh
```
For Windows:
```shell
./bootstrap.sh
```

## Licensing

Released under the MIT license.