# Number Guessing Game

A small terminal game written in C: guess a randomly generated number before your ten attempts run out.

**C · Terminal game · Learning project**

## How it works

- The program chooses a number from **0 to 99**.
- You have **10 attempts** to find it.
- After a failed game, you can play again or exit.
- The terminal interface is in Portuguese.

## Learning focus

Loops, conditional statements, functions, console input and pseudorandom numbers. Created during the first semester at IPB.

## Build and run

The current source needs `#include <stdlib.h>` and `#include <time.h>` added before it can be compiled reliably with modern C compilers. After adding those headers, build with GCC:

```sh
gcc main.c -o adivinha-numero
./adivinha-numero
```

On Windows, run `.\adivinha-numero.exe`. The prompt currently says “0 to 100”; the actual generated range is 0 to 99.

## Related projects

[Version with difficulty levels](https://github.com/fabioxyz/adivinha-numero-niveis-c) · [All C projects](https://github.com/fabioxyz/projetos-c)
