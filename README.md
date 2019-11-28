# R-project

# CMD

doc : `make help`

assign remote default repo:
- `make loadcran`

install package:
  - `make installpackage` # For windows run cmd as admin

run project:
  - `make runproject`

# Dependencies

## Linux

Debian:
  - `sudo apt-get install r-base-core gcc`

Arch:
  - `sudo pacman -Syu r gcc gcc-fortran`

## Windows

### Downloads link

R : `https://cran.r-project.org/bin/windows/base/`

GCC : `https://osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/`

Make : `http://gnuwin32.sourceforge.net/packages/make.htm`

### After downloads and install

set path with `autoconfpath.bat`
