
# LC3

Basic Implementation of an LC-3 VM.

Follows the general Instruction Set outlined by the provided LC-3 Documentation,
and is able to run LC-3 specific programs.

# Demo

Two object files have been provided from an external source for testing.

Simply drag them to the provided executable file, or run in the command line:
```
./tmr-vm.exe 2048.obj
```

# Compilation

Compilation was tested only using the libc standard library.
Results may vary for other related libraries.

Windows:
```
gcc -o ./bin/tmr-vm ./src/lc3_windows.c
```

Linux:
```
gcc -o ./bin/tmr-vm ./src/lc3_unix.c
```
