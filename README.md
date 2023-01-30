About yggdrasil
===============

Home: https://github.com/cropsinsilico/yggdrasil

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/yggdrasil-feedstock/blob/main/LICENSE.txt)

Summary: A framework for connecting computational models from multiple languages.

Development: https://github.com/cropsinsilico/yggdrasil

Documentation: https://cropsinsilico.github.io/yggdrasil

The Crops in Silico (CiS) framework, yggdrasil, provides support for
connecting scientific models written in different programming languages.
To connect two models, modelers add communications interfaces to the model code
and provide declarative specification files that identfy the
models that should be run and the inputs and outputs those models
expect. yggdrasil uses this information to launch the models
on parallel processes and orchestrate asynchronous communication between them.
Although designed for connecting crop models, yggdrasil can be used to
connect scientific models from any domain.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=6228&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/yggdrasil-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil-green.svg)](https://anaconda.org/conda-forge/yggdrasil) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.svg)](https://anaconda.org/conda-forge/yggdrasil) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.svg)](https://anaconda.org/conda-forge/yggdrasil) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.svg)](https://anaconda.org/conda-forge/yggdrasil) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.astropy-green.svg)](https://anaconda.org/conda-forge/yggdrasil.astropy) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.astropy.svg)](https://anaconda.org/conda-forge/yggdrasil.astropy) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.astropy.svg)](https://anaconda.org/conda-forge/yggdrasil.astropy) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.astropy.svg)](https://anaconda.org/conda-forge/yggdrasil.astropy) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.c-green.svg)](https://anaconda.org/conda-forge/yggdrasil.c) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.c.svg)](https://anaconda.org/conda-forge/yggdrasil.c) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.c.svg)](https://anaconda.org/conda-forge/yggdrasil.c) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.c.svg)](https://anaconda.org/conda-forge/yggdrasil.c) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.dev-green.svg)](https://anaconda.org/conda-forge/yggdrasil.dev) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.dev.svg)](https://anaconda.org/conda-forge/yggdrasil.dev) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.dev.svg)](https://anaconda.org/conda-forge/yggdrasil.dev) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.dev.svg)](https://anaconda.org/conda-forge/yggdrasil.dev) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.docs-green.svg)](https://anaconda.org/conda-forge/yggdrasil.docs) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.docs.svg)](https://anaconda.org/conda-forge/yggdrasil.docs) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.docs.svg)](https://anaconda.org/conda-forge/yggdrasil.docs) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.docs.svg)](https://anaconda.org/conda-forge/yggdrasil.docs) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.fortran-green.svg)](https://anaconda.org/conda-forge/yggdrasil.fortran) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.fortran.svg)](https://anaconda.org/conda-forge/yggdrasil.fortran) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.fortran.svg)](https://anaconda.org/conda-forge/yggdrasil.fortran) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.fortran.svg)](https://anaconda.org/conda-forge/yggdrasil.fortran) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.mpi-green.svg)](https://anaconda.org/conda-forge/yggdrasil.mpi) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.mpi.svg)](https://anaconda.org/conda-forge/yggdrasil.mpi) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.mpi.svg)](https://anaconda.org/conda-forge/yggdrasil.mpi) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.mpi.svg)](https://anaconda.org/conda-forge/yggdrasil.mpi) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.pygments-green.svg)](https://anaconda.org/conda-forge/yggdrasil.pygments) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.pygments.svg)](https://anaconda.org/conda-forge/yggdrasil.pygments) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.pygments.svg)](https://anaconda.org/conda-forge/yggdrasil.pygments) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.pygments.svg)](https://anaconda.org/conda-forge/yggdrasil.pygments) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.r-green.svg)](https://anaconda.org/conda-forge/yggdrasil.r) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.r.svg)](https://anaconda.org/conda-forge/yggdrasil.r) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.r.svg)](https://anaconda.org/conda-forge/yggdrasil.r) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.r.svg)](https://anaconda.org/conda-forge/yggdrasil.r) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.rmq-green.svg)](https://anaconda.org/conda-forge/yggdrasil.rmq) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.rmq.svg)](https://anaconda.org/conda-forge/yggdrasil.rmq) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.rmq.svg)](https://anaconda.org/conda-forge/yggdrasil.rmq) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.rmq.svg)](https://anaconda.org/conda-forge/yggdrasil.rmq) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.testing-green.svg)](https://anaconda.org/conda-forge/yggdrasil.testing) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.testing.svg)](https://anaconda.org/conda-forge/yggdrasil.testing) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.testing.svg)](https://anaconda.org/conda-forge/yggdrasil.testing) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.testing.svg)](https://anaconda.org/conda-forge/yggdrasil.testing) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.trimesh-green.svg)](https://anaconda.org/conda-forge/yggdrasil.trimesh) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.trimesh.svg)](https://anaconda.org/conda-forge/yggdrasil.trimesh) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.trimesh.svg)](https://anaconda.org/conda-forge/yggdrasil.trimesh) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.trimesh.svg)](https://anaconda.org/conda-forge/yggdrasil.trimesh) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-yggdrasil.zmq-green.svg)](https://anaconda.org/conda-forge/yggdrasil.zmq) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/yggdrasil.zmq.svg)](https://anaconda.org/conda-forge/yggdrasil.zmq) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/yggdrasil.zmq.svg)](https://anaconda.org/conda-forge/yggdrasil.zmq) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/yggdrasil.zmq.svg)](https://anaconda.org/conda-forge/yggdrasil.zmq) |

Installing yggdrasil
====================

Installing `yggdrasil` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `yggdrasil, yggdrasil.astropy, yggdrasil.c, yggdrasil.dev, yggdrasil.docs, yggdrasil.fortran, yggdrasil.mpi, yggdrasil.pygments, yggdrasil.r, yggdrasil.rmq, yggdrasil.testing, yggdrasil.trimesh, yggdrasil.zmq` can be installed with `conda`:

```
conda install yggdrasil yggdrasil.astropy yggdrasil.c yggdrasil.dev yggdrasil.docs yggdrasil.fortran yggdrasil.mpi yggdrasil.pygments yggdrasil.r yggdrasil.rmq yggdrasil.testing yggdrasil.trimesh yggdrasil.zmq
```

or with `mamba`:

```
mamba install yggdrasil yggdrasil.astropy yggdrasil.c yggdrasil.dev yggdrasil.docs yggdrasil.fortran yggdrasil.mpi yggdrasil.pygments yggdrasil.r yggdrasil.rmq yggdrasil.testing yggdrasil.trimesh yggdrasil.zmq
```

It is possible to list all of the versions of `yggdrasil` available on your platform with `conda`:

```
conda search yggdrasil --channel conda-forge
```

or with `mamba`:

```
mamba search yggdrasil --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search yggdrasil --channel conda-forge

# List packages depending on `yggdrasil`:
mamba repoquery whoneeds yggdrasil --channel conda-forge

# List dependencies of `yggdrasil`:
mamba repoquery depends yggdrasil --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [Anaconda-Cloud](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating yggdrasil-feedstock
============================

If you would like to improve the yggdrasil recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/yggdrasil-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/r](https://github.com/conda-forge/r/)
* [@langmm](https://github.com/langmm/)

