# STARE_Overview
Basic tutorial for STARE


## Tested Systems

### MacOS
    OS              : macOS 15.4 (24E248) Sequoia
        Kernel      : Darwin 24.4.0
        Architecture: arm64 (Little Endian)

        Model       : MacBook Pro (16-inch, 2021) (MacBookPro18,2)
        CPU         : Apple M1 Max @ 3.20GHz x 10 cores
        RAM         : 32GB LPDDR5-6400 MHz (unified memory, GPU can use)
        GPU         : Apple M1 Max 32 cores (4,096 Arithmetic Logic Units (ALUs))
        HD:         : 1 TB

        Shell       : bash 5.2.37
        clang       : 17.0.0 (clang-1700.0.13.3)
        XCode       : 16.3
        Homebrew    : Homebrew 4.4.27
        Conda       : conda 25.3.0
                        base                     /Users/mbauer/miniconda3                   Python 3.12.4
                        stare                 *  /Users/mbauer/miniconda3/envs/stare        Python 3.13.2

### Linux
    OS              : Ubuntu 24.04.2 LTS (Noble Numbat)
        Kernel      : 6.8.0-57-generic
        Architecture: x86_64 (Little Endian)

        Model       : HP OMEN by HP Obelisk Desktop 875-1xxx
        CPU         : Intel i7-9700K @ 3.60GHz x 8 cores (512 KB L1. 2 MB L2 and 12 MB L3 Caches)
        RAM         : 64 GB DDR4-2666 MHz (4 x 16 GB)
        GPU         : NVIDIA GeForce RTX 2080 SUPER
                        CUDA Cores           : 3072
                        Total Memory         : 8192 MB
                        CUDA Toolkit         : 12.0
        HD:         : 6.5 TB

        Shell       : bash 5.2.21
        gcc         : 13.3.0
        Conda       : conda 25.3.0
                        base                     /home/mbauer/miniconda3                   Python 3.12.7
                        stare                 *  /home/mbauer/miniconda3/envs/stare        Python 3.12.7

### Windows
    OS              : Windows 11 v24H2
        Model       : HP OMEN by HP Obelisk Desktop 875-1xxx

--------------------------------------

## Basic Requirements

- Python 3 (tested up to 3.13.2)
- CMake (tested with 4.0.0)
- C++ Compiler (tested with clang 17.0.0 and gcc 13.3.0)
- Conda (tested with 25.3.0)
    - Key packages
        - cartopy                   0.24.0
        - cython                    3.0.12
        - dask                      2025.3.0
        - **geopandas**             1.0.1
        - matplotlib                3.10.1
        - netcdf4                   1.7.2
        - **numpy**                 2.2.4
        - **pandas**                2.2.3
        - pyshp                     2.3.1
        - **shapely**               2.0.7
        - swig                      4.3.0
        - xarray                    2025.3.1
        - yaml                      0.2.5
        - zarr                      3.0.6
