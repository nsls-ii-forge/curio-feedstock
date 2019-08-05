About curio
===========

Home: https://curio.readthedocs.org/

Package license: BSD 3-clause

Feedstock license: BSD 3-Clause

Summary: The coroutine concurrency library.

Curio is a library for performing concurrent I/O and common system programming
tasks such as launching subprocesses and farming work out to thread and process
pools. It uses Python coroutines and the explicit async/await syntax introduced
in Python 3.5. Its programming model is based on cooperative multitasking and
existing programming abstractions such as threads, sockets, files, subprocesses,
locks, and queues. You'll find it to be small and fast.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/curio-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-curio-green.svg)](https://anaconda.org/nsls2forge/curio) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/curio.svg)](https://anaconda.org/nsls2forge/curio) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/curio.svg)](https://anaconda.org/nsls2forge/curio) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/curio.svg)](https://anaconda.org/nsls2forge/curio) |

Installing curio
================

Installing `curio` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `curio` can be installed with:

```
conda install curio
```

It is possible to list all of the versions of `curio` available on your platform with:

```
conda search curio --channel nsls2forge
```




Updating curio-feedstock
========================

If you would like to improve the curio recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/curio-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@jochym](https://github.com/jochym/)
* [@scopatz](https://github.com/scopatz/)

