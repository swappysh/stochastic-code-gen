# Environment Setup
1. `conda env create -f environment-(cpu/gpu).yml`
2. `conda activate codegen-(cpu/gpu)`

#### Saving Changes
- `conda env export -n codegen-(cpu/gpu) -f environment-(cpu/gpu).yml --no-builds`
