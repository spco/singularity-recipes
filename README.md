# singularity-recipes
This repository contains the recipes and associated files for Singularity containers for the MILC (and soon TROVE) benchmarks(s).

A quick primer: on a system with singularity installed,

```
singularity pull --name spco-singularity-recipes-milc-gcc.simg shub://spco/singularity-recipes:milc-gcc
singularity run spco-singularity-recipes-milc-gcc.simg
```

will pull and run the container. Go to https://www.singularity-hub.org/collections/951 for the full collection of images available.
