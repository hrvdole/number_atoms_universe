number_of_galaxies_in_universe_with_JWST_SMACS0723.ipynb
by Pr Hervé Dole, IAS, Université Paris-Saclay
updated: 20241215

The notebook computes the number of atoms in the Observable Universe,
based on the extrapolation of deep JWST images of SMACS0723.

you need to have a fits imnage of : JWST f356 of SMACS0723

1. compute the number of galaxies in SMACS0723
2. compute the sky area covered by SMACS0723 and the factor needed to cover the whole sky
3. compute the mass of the sun, and the number of atoms in the sun
4. compute the number of stars in a galaxy

We multiply the number of atoms in a star * numbers of stars in a galaxy *
number of galaxies in the observable universe (as extrapolated from JWST
SMACS0723) and get ~1.e79 atoms.

If we correct for the missin g baryons we reach about 1.e80 atoms.
