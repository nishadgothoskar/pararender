Adapted from https://github.com/NVlabs/nvdiffrast

## Installation

Install necessary dependicies

```
sudo apt-get update 
sudo apt-get install pkg-config \
    libglvnd0 \
    libgl1 \
    libglx0 \
    libegl1 \
    libgles2 \
    libglvnd-dev \
    libgl1-mesa-dev \
    libegl1-mesa-dev \
    libgles2-mesa-dev \
    libglu1-mesa-dev \
    cmake \
    curl
```

and `numpy` and `pytorch`. Then install `pararender` with

```
python setup.py develop
```
