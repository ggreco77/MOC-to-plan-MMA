# Multi-Order-Coverage-data-structure-to-plan-multi-messenger-observations
We describe the use of Multi Order Coverage (MOC) maps as a practical way to manage complex regions of the sky for the planning of multi-messenger observations.

# Instructions

Packages required to reproduce the tutorial are
* [mocpy](https://cds-astro.github.io/mocpy/install.html)
* [cdshealpix](https://cds-astro.github.io/cds-healpix-python/install.html)
* [astropy](https://docs.astropy.org/en/stable/install.html)
* [astroplan](https://astroplan.readthedocs.io/en/latest/installation.html)
* [ipyaladin](https://github.com/cds-astro/ipyaladin)

The [tutorial](https://github.com/ggreco77/MOC-to-plan-MMA/blob/main/Multi%20Order%20Coverage%20data%20structure%20to%20plan%20multi-messenger%20observations.ipynb) is tested in Python 3.8.5 with the module versions: mocpy 0.10.0, cdshealpix 0.6.1, astropy 5.0 and astroplan 0.8 and ipyaladin. 
For Installing packages using pip and virtual environments, follow the instruction in the  Python Packaging User Guide [here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

### Aladin Desktop Software
The results can be visualized in the [Aladin Desktop Software](https://aladin.u-strasbg.fr/AladinDesktop/). To install it, follow the instructions below.

Download the [Aladin.jar](https://aladin.u-strasbg.fr/java/Aladin.jar) from the [Aladin download page](https://aladin.u-strasbg.fr/java/nph-aladin.pl?frame=downloading). Execute it from a terminal by typing:

     $ java -Xmx2g -jar Aladin.jar
     
The flag -Xmx<ammount of memory> specifies the maximum memory allocation pool for a JVM. Here 2GB of memory is allocated. For GW sky localizations with nside=2048, increase the memory allocated up to 3GB, -Xmx3g.
