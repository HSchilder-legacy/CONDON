# CONDON

Welcome to condon to have a look at program CONDON, which calculates the paramagnetic part of molar magnetic susceptibility, named CHI, and is written in standard FORTRAN77. The term CONDON was taken from E. U. Condon, G. H. Shortley, "The Theory of Atomic Spectra". The calculation of CHI, mostly done for transition metal and lanthanide complexes, is embedded in a fitting procedure "Levenberg-Marquardt", which may be used to get ligand field parameters, if experimental CHI values are known. Formulas for energy levels of ions are taken from the book just cited, formulas concerning ligand fields and magnetism are taken from J. S. Griffith, "The Theory of Transition-Metal Ions", and B. G. Wybourne, "Spectroscopic Properties of Rare Earths".

CONDON calculates the magnetic susceptibility of mononuclear and exchange-coupled homodinuclear d--d and f--f systems as well as heterodinuclear d--s and f--s systems. Operators of interelectronic repulsion, spin-orbit coupling, ligand-field effect (cubic, uniaxial, orthorhombic), isotropic exchange coupling within dinuclear units, and applied magnetic field are simultaneously applied, and no approximations, e.g. for weak or strong ligand field, are made. Either all microstates, up to 3432 for f electrons, or the Russell-Saunders ground term serve as a basis. The traditional approach of Van Vleck is included, too.  

CONDON is free software, covered by the GNU General Public Licence, runs under LINUX, UNIX, and WINDOWS, and additional libraries may be helpful, but are not necessary. An allocation of memory at run time is possible, if an appropriate compiler is available (e.g. g77).  

The program CONDON was designed, developed and programmed by Helmut Schilder who sadly passed away in February 2015.
