About pyqt
==========

Home: http://www.riverbankcomputing.co.uk/software/pyqt

Package license: Commercial, GPL-2.0, GPL-3.0

Feedstock license: BSD 3-Clause

Summary: Python binding of the cross-platform GUI toolkit Qt.

"PyQt is a set of Python v2 and v3 bindings for The Qt Company's Qt
application framework and runs on all platforms supported by Qt including
Windows, MacOS/X and Linux. PyQt5 supports Qt v5. PyQt4 supports Qt v4 and
will build against Qt v5. The bindings are implemented as a set of Python
modules and contain over 1,000 classes."


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/viscid-hub/pyqt-feedstock/master.svg?label=Linux)](https://circleci.com/gh/viscid-hub/pyqt-feedstock)
[![OSX](https://img.shields.io/travis/viscid-hub/pyqt-feedstock/master.svg?label=macOS)](https://travis-ci.org/viscid-hub/pyqt-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/viscid-hub/pyqt-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/viscid-hub/pyqt-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pyqt-green.svg)](https://anaconda.org/viscid-hub/pyqt) | [![Conda Downloads](https://img.shields.io/conda/dn/viscid-hub/pyqt.svg)](https://anaconda.org/viscid-hub/pyqt) | [![Conda Version](https://img.shields.io/conda/vn/viscid-hub/pyqt.svg)](https://anaconda.org/viscid-hub/pyqt) | [![Conda Platforms](https://img.shields.io/conda/pn/viscid-hub/pyqt.svg)](https://anaconda.org/viscid-hub/pyqt) |

Installing pyqt
===============

Installing `pyqt` from the `viscid-hub` channel can be achieved by adding `viscid-hub` to your channels with:

```
conda config --add channels viscid-hub
```

Once the `viscid-hub` channel has been enabled, `pyqt` can be installed with:

```
conda install pyqt
```

It is possible to list all of the versions of `pyqt` available on your platform with:

```
conda search pyqt --channel viscid-hub
```




Updating pyqt-feedstock
=======================

If you would like to improve the pyqt recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`viscid-hub` channel, whereupon the built conda packages will be available for
everybody to install and use from the `viscid-hub` channel.
Note that all branches in the viscid-hub/pyqt-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
