# GTVimageVect
Source code of "Geometric Total Variation for Image Vectorization, Zooming and Pixel Art Depixelizing"



## Installation


To use this source code, you need to install the following dependencies:
   - **DGTal library** (current version or at least [commit 0e13036](https://github.com/DGtal-team/DGtal/commit/0e13036afedee920373a2460afd02e2a21660baa)), on Linux/Mac just follow these steps:
     - Install (if not already present), the boost dependancies (see https://www.boost.org).
     For instance on linux you can install the following package: sudo apt-get install `libboost-dev libboost-system-dev libboost-program-options-dev`(the `libboost-program-options-dev` is not mandatory for DGtal but is used by our project)
     - `git clone git@github.com:DGtal-team/DGtal.git`
     - `cd DGtal; mkdir build; cd build`
     - `cmake .. -DBUILD_TESTING=OFF -DBUILD_EXAMPLES=OFF -DCMAKE_BUILD_TYPE:string="Release";`
     - `make;`
     - Not mandatory `make install`.
     - For any problem, don't hesitate to contact the DGtal team on the [GitHub repository](https://github.com/DGtal-team/DGtal)
     On windows or more details see instructions [here](https://dgtal-team.github.io/doc-nightly/moduleBuildDGtal.html).
   - **cairo**
      The installation details (Linux/MacOS/Windows) are on the website: https://www.cairographics.org/download/
   - **boost programm options** by default the application use the package `libboost-program-options-dev`. You can use you default package manager to install it.


The installation of the code is then easy:
   - From the git command:
     `git clone git@github.com:kerautret/GTVimageVect.git`
     `cd GTVimageVect; mkdir build; cd build;`
     Then you start to build the code: (you can remove the DGtal path if you make a global installation of DGtal.
     `cmake .. -DDGtal_DIR="/fullpath_to_yourParent_DGtal_dir/DGtal/build"`
     `make`
     
