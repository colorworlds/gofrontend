# A Go 前端

Ian Lance Taylor
Last update 15 June 2014

这是一个[Go 语言](http://golang.org/)的编译器前端。
The frontend was originally developed at Google, and was released in November 2009. 
It was originally written by Ian Lance Taylor.

It was originally written for [GCC](http://gcc.gnu.org/). As of this writing it only supports GCC, but the GCC support has been separated from the rest of the frontend, so supporting another compiler is feasible.

The go subdirectory holds the frontend source code. This is mirrored to the gcc/go subdirectory in the GCC repository.

The libgo subdirectory holds the library source code. This is a copy of the main Go library with various changes appropriate for this compiler. The main Go library is hosted at <http://go.googlesource.com/go>, in the src directory. The libgo subdirectory is mirrored to the libgo subdirectory in the gcc repository.

## Legal Matters

To contribute patches to the files in this directory, please see [Contributing to the gccgo frontend](http://golang.org/doc/gccgo_contribute.html).

The master copy of these files is hosted in [Gerrit](http://go.googlesource.com/gofrontend) (there is a mirror at [Github](http://github.com/golang/gofrontend)). Changes to these files require signing a Google contributor license agreement. If you are the copyright holder, you will need to agree to the [Google Individual Contributor License Agreement](http://code.google.com/legal/individual-cla-v1.0.html). This agreement can be completed online.

If your organization is the copyright holder, the organization will need to agree to the [Google Software Grant and Corporate Contributor License Agreement](http://code.google.com/legal/corporate-cla-v1.0.html).

If the copyright holder for your code has already completed the agreement in connection with another Google open source project, it does not need to be completed again.
