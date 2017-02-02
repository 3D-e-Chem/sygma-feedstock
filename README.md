About sygma
===========

Home: https://github.com/3D-e-Chem/sygma

Package license: GPL

Feedstock license: BSD 3-Clause

Summary: 



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/sygma-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/sygma-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/sygma-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/sygma-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/sygma-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/sygma-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/3D-e-Chem/sygma/badges/version.svg)](https://anaconda.org/3D-e-Chem/sygma)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/3D-e-Chem/sygma/badges/downloads.svg)](https://anaconda.org/3D-e-Chem/sygma)

Installing sygma
================

Installing `sygma` from the `3D-e-Chem` channel can be achieved by adding `3D-e-Chem` to your channels with:

```
conda config --add channels 3D-e-Chem
```

Once the `3D-e-Chem` channel has been enabled, `sygma` can be installed with:

```
conda install sygma
```

It is possible to list all of the versions of `sygma` available on your platform with:

```
conda search sygma --channel 3D-e-Chem
```




Updating sygma-feedstock
========================

If you would like to improve the sygma recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`3D-e-Chem` channel, whereupon the built conda packages will be available for
everybody to install and use from the `3D-e-Chem` channel.
Note that all branches in the conda-forge/sygma-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
