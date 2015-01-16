Master Branch: [![Build Status](https://travis-ci.org/predictiveecology/SpaDES.svg?branch=master)](https://travis-ci.org/predictiveecology/SpaDES)

Development Branch: [![Build Status](https://travis-ci.org/predictiveecology/SpaDES.svg?branch=development)](https://travis-ci.org/predictiveecology/SpaDES)

-----

# Spatial Discrete Event Simulation (SpaDES)

*Develop and run spatially explicit discrete event simulation models.*

Easily implement a variety of simulation models, with a focus on spatially explicit agent based models. The core simulation components are built upon a discrete event simulation framework that facilitates modularity, and easily enables the user to include additional functionality by running user-built simulation modules. Included are numerous tools to visualize raster and other maps.

**Website:** [https://github.com/predictiveecology/SpaDES](https://github.com/predictiveecology/SpaDES)

## Installation

Download the source tarball (.tar.gz) or windows package binary (.zip):

+ Current stable release:
    - [Windows binary (.zip)](https://github.com/predictiveecology/SpaDES/raw/master/SpaDES_0.4.0.zip)
    - [Source package (.tar.gz)](https://github.com/predictiveecology/SpaDES/raw/master/SpaDES_0.4.0.tar.gz)
+ Development version (unstable):
    - [Windows binary (.zip)](https://github.com/predictiveecology/SpaDES/raw/development/SpaDES_0.5.0.9000.zip)
    - [Source package (.tar.gz)](https://github.com/predictiveecology/SpaDES/raw/development/SpaDES_0.5.0.9000.tar.gz)

Alternatively, install `SpaDES` directly from GitHub. You will need the `devtools` package, as well as the appropriate development libraries for your operating system (e.g., Windows users should install [Rtools](http://cran.r-project.org/bin/windows/Rtools/)). In order to build the vignettes from source (which is done when installing a package from GitHub) you need to have a LaTeX distribution installed. We recommend [TexLive](https://www.tug.org/texlive/).

    install.packages("devtools")
    library("devtools")
	
    install_github("predictiveecology/SpaDES") # stable
    install_github("predictiveecology/SpaDES", ref="development") # unstable
    
The suggested package `fastshp` can be installed with:

    install_github("s-u/fastshp")

If the install from GitHub fails during vignette building, you can skip this step (and avoid having to install LaTeX) by using `install_github("predictiveecology/SpaDES", ref="development", build=FALSE)`.

## Reporting bugs

Contact us via the package GitHub site: [https://github.com/predictiveecology/SpaDES/issues](https://github.com/predictiveecology/SpaDES/issues).
