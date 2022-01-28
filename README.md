## ISOBL_model_out

This repository contans large-eddy simulation model output. The simulations are of the boundary layer beneath a melting ice shelf. This model ouput underpins the submitted manuscript *Regimes and transitions in the basal melting of Antarctic ice shelves* submitted to the Journal of Physical Oceanography (December 2021).

**Contents:**

Each folder contains output from a single simulation in a netcdf file "ISOBL_model_output.nc".

Naming convention refers to the free stream velocity (U) and the thermal driving (T) for eaach case, e.g. U07_N005 --> U=0.7 cm/s, T\*=0.005 degrees C.

Dataset consists of profiles in the wall[ice]-normal direction (y) over time. Profiles are all averages over the horizontal (x-z) plane.

Note that in the manuscript "Regimes and transitions in the basal melting of Antarctic ice shelves" I rave renamed the co-ordinate "y" as "z" and vice-versa, as "z" is typically used/easily recognised as the vertical co-ordinate.
