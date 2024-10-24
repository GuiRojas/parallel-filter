# parallel-filter

## Compiling
`export OMP_NUM_THREADS=16`
`clang -fsanitize=undefined -O3 -std=c11 -fopenmp -Wshadow -o dist dist.c`

## Running
`./dist tower.bmp out.bmp`
