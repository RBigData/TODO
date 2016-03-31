# TODO

A to-do list of projects.  Not a place for bugs in existing packages (use the package's GitHub issue tracker).


## Non-Functional/Incomplete
* [pbdADIOS](https://github.com/go-ski/pbdADIOS)
    * **Quick Description**: Interface to the ADIOS I/O library.
    * **Needs**: Documentation, vignette, higher-level interface, possible memory management issues (test with valgrind)
* [pbdMR](https://github.com/wrathematics/pbdMR)
    * **Quick Description**: Mapreduce over MPI
    * **Needs**: Finish implementing map and reduce primitives, documentation, vignette.
* [pbdRchive](https://github.com/RBigData/pbdRchive)
    * **Quick Description**: A set of scripts for managing a linux environment.  Have things like nightly pbdR package builds, ppa/binary distributions, measure/log package statistics from CRAN/GitHub, etc.
    * **Needs**: See description above.


## Needs Love
* [pbdML](https://github.com/RBigData/pbdML)
    * **Quick Description**: Machine learning algorithms implemented on top of pbdMPI and/or pbdDMAT.
    * **Needs**: better tests, more methods
* [hpcvis](https://github.com/RBigData/hpcvis)
    * **Quick Description**: Plotters for MPI and performance counter (PAPI) profilers
    * **Needs**: more pbdPAPI plots, more than barplots for MPI profilers, eventual integration with TAU
* [pbdSBASE](https://github.com/wrathematics/pbdSBASE)
    * **Quick Description**: Sparse matrix/vector methods over PETSc.
    * **Needs**: better build scripts, integration into pbdDMAT, vignette/documentation, better configure/build testing (and/or finish pbdSSLAP)
    

## Website
* Move to static hosting for documentation, vignettes, package sources/binaries, etc (see pbdRchive above).
* Update/rewrite [installation instructions](https://github.com/RBigData/installation-instructions) in markdown for non-terrible html generation
* Fix [staticdocs](https://github.com/hadley/staticdocs) to work with pbd packages; generate [website documentation](https://github.com/RBigData/RBigData.github.io/tree/master/documentation) with fixed staticdocs.


## Unstarted Projects

#### High Priority
* Parallel IO tools
* dplasma integration in pbdBASE/pbdDMAT

#### Nice to Have
* Scheduler integration for the client/server
