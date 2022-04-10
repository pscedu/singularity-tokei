![Status](https://github.com/pscedu/singularity-tokei/actions/workflows/main.yml/badge.svg)
![Status](https://github.com/pscedu/singularity-tokei/actions/workflows/pretty.yml/badge.svg)
![Issue](https://img.shields.io/github/issues/pscedu/singularity-tokei)
![forks](https://img.shields.io/github/forks/pscedu/singularity-tokei)
![Stars](https://img.shields.io/github/stars/pscedu/singularity-tokei)
![License](https://img.shields.io/github/license/pscedu/singularity-tokei)

# singularity-tokei
```console
===============================================================================
 Language            Files        Lines         Code     Comments       Blanks
===============================================================================
 BASH                    4           49           30           10            9
 JSON                    1         1332         1332            0            0
 Shell                   1           49           38            1           10
 TOML                    2           77           64            4            9
-------------------------------------------------------------------------------
 Markdown                5         1355            0         1074          281
 |- JSON                 1           41           41            0            0
 |- Rust                 2           53           42            6            5
 |- Shell                1           22           18            0            4
 (Total)                           1471          101         1080          290
-------------------------------------------------------------------------------
 Rust                   19         3416         2840          116          460
 |- Markdown            12          351            5          295           51
 (Total)                           3767         2845          411          511
===============================================================================
 Total                  32         6745         4410         1506          829
===============================================================================
```

Singularity recipe for [tokei](https://github.com/XAMPPRocky/tokei).

## Installing the container on Bridges 2
Copy the

* `SIF` file
* and the `tokei` script

to `/opt/packages/tokei/12.1.2`.

Copy the file `modulefile.lua` to `/opt/modulefiles/tokei` as `12.1.2.lua`.

## Building the image using the recipe
### To build the image locally
Run the script `build.sh` to build image locally.

```
bash ./build.sh
```

### To build the image remotely
Run the script `rbuild.sh` to build image remotely.

```
bash ./rbuild.sh
```

## To run tests
To run the available tests, run the command

```
bash ./test.sh
```

---
Copyright © 2020-2021 Pittsburgh Supercomputing Center. All Rights Reserved.

The [Biomedical Applications Group](https://www.psc.edu/biomedical-applications/) at the [Pittsburgh Supercomputing
Center](http://www.psc.edu) in the [Mellon College of Science](https://www.cmu.edu/mcs/) at [Carnegie Mellon University](http://www.cmu.edu).
