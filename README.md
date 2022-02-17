## ZStruct
Zstruct code based on original implementation from https://github.com/ZimmermanGroup/ZStruct modified in https://github.com/jakobandersen/ZStruct and again modified in this project to disable qsub jobs and remove atom limit (original limit of 35 atoms, now 1000 atoms.

## Compile
```
make
```
This creates a zstruct.exe that can be run with either one or two input molecules.
```
./zstruct.exe -250 1000 1 0
```
```
./zstruct.exe -250 1000 1 1
```
