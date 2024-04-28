### Guide to COLAB

In this folder, you will find 4 Colab notebooks:

1. **GCR_fit_function**
   - Experimental data (PAMELA) of cosmic ray flux as a function of kinetic energy for protons, helium, and boron nuclei are taken. A fit is performed to find an analytical expression. Upon finding the expression, it is observed that it is not analytically integrable, so a function that majorizes it at every point is sought for applying the optimized rejection Monte Carlo method.

2. **Monte_Carlo_Methods_GCR**
   - Two different methods are tested to extract nucleon energy from the distribution obtained from the fit: linear search and optimized rejection. The latter is chosen for being faster.

3. **Calculating_Mars_Travel_Dose**
   - Results obtained from the previous Colabs are combined to find an absorbed dose value for a 700-day journey. Thicknesses of aluminum and silicon are also included to simulate the spaceship.

4. **Dose_with_Gaussian_E**
   - The value obtained in Colab 3 is compared with the value obtained by extracting kinetic energy of nucleons from a Gaussian distribution with a mean of 1 GeV and variance of 200 MeV (as done in class). Aluminum and silicon thicknesses are also added here.
