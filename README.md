number_of_galaxies_in_universe_with_JWST_SMACS0723.ipynb
by Pr Hervé Dole, IAS, Université Paris-Saclay
updated: 20241215

The notebook computes the number of atoms in the Observable Universe,
based on the extrapolation of deep JWST images of SMACS0723.

You need to have a fits image of : JWST f356 of SMACS0723 to
compute the number of galaxies. Otherwise, read the comments
to get the number.

The notebook organisation is the following:

1. compute the number of galaxies in SMACS0723
2. compute the sky area covered by SMACS0723 and the factor needed to cover the whole sky
3. compute the mass of the sun, and the number of atoms in the sun
4. compute the number of stars in a galaxy

We multiply the number of atoms in a star * numbers of stars in a galaxy *
number of galaxies in the observable universe (as extrapolated from JWST
SMACS0723) and get ~1.e79 atoms.

If we correct for the missing baryons we reach about 1.e80 atoms.

References:
- https://youtu.be/74EGTJElxGQ by Physics Explained, pen and pencil version.
- Fukugita & Peebles 2004 ApJ : https://arxiv.org/abs/astro-ph/0406095 
- Nicastro et al., 2018, Nat : https://arxiv.org/abs/1806.08395 
- Ettori, 2003, MNRAS : https://arxiv.org/abs/astro-ph/0305296 
- JWST data download : https://mast.stsci.edu/search/ui/#/jwst/results?resolve=true&target=SMACS0723&data_types=image,measurements&instruments=NIRCAM&optical_element=F356W&custom_col_sel_0=productLevel&custom_col_val_0=3&radius=3&radius_units=arcminutes&useStore=false
