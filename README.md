# COSP (Surface Lidar Fork)

COSP is the CFMIP Observation Simulator Package.

This is a fork of [CFMIP/COSPv1](https://github.com/CFMIP/COSPv1) with
experimental support for surface lidar. It includes support for two
wavelengths: 532 nm and 1064 nm (Rayleigh and Mie scattering).

Known issues:

- Mie scattering from ice is treated as the same as Mie scattering from liquid.
- No precipitation or aerosol simulation (not present in COSP/ACTSIM).

Configuration options:

- `surface_lidar` – Surface lidar switch (1 – surface, 0 – spaceborne)
- `lidar_wavelength` – Lidar wavelength (nm)

Also see the original [README](README.txt).
