# Libasm

## Overview

I created a C function using in assembly language.

## Requirement

- macOS
- clang

## Usage

```
git clone ...
cd Libasm
make
```

A library called libasm.a will be created, so compile it with the main file you want to use.  
For example, if you have main.c and libasm.a in your current directory:

```
gcc main.c -L . -lasm
```

## sample

You can easily test the performance of Libasm

```
make
make test
./main
```

## Features


The following function is written in assembly.

- read
- strcmp
- strcpy
- strdup
- strlen
- write

## Author

[twitter](https://twitter.com/Kotabrog)

## Licence

[MIT](https://github.com/kotabrog/Libasm/blob/main/LICENSE)