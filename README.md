# build-tools
Ubuntu (rolling) with build tools

[![singularity-deploy](https://github.com/shub-fuzz/build-tools/actions/workflows/builder.yml/badge.svg?branch=main)](https://github.com/shub-fuzz/build-tools/actions/workflows/builder.yml)

- __What__ is [Singularity](https://sylabs.io/singularity/)?  
  A containerization system primarily used by the scientific community on high-performance computing (HPC).
  On many University HPC systems, docker is not allowed, but singularity is availble because it runs with 
  user level permisions.  
- __Why__?  
  Fuzzing on HPC!  
  Universities have trememdous resources available in HPC clusters that can be used to support 
  large-scale fuzzing evaluations.

