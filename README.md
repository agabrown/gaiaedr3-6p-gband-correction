# gaiaedr3-6p-gband-correction
G-band photometry corrections for Gaia EDR3 sources with 2-parameter or 6-parameter astrometric solutions.

The Jupyter notebook in this repository presents a Python function for calculating the corrections to the G-band photometry for Gaia EDR3 sources with a 2-parameter or 6-parameter astrometric solution. The code is listed in the appendix of [Gaia Collaboration et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A%26A...649A...1G/abstract), and implements the formulae presented in [Riello et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021A%26A...649A...3R/abstract).

__NOTE: THIS CODE SHOULD NOT BE USED FOR GAIA DR3 (i.e. the `gaiadr3.gaia_source` table) DATA. THE GAIA DR3 PHOTOMETRY ALREADY
INCLUDES THE G-BAND CORRECTIONS.__
Copyright: Anthony G.A. Brown, Leiden University
