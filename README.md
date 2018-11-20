rstool
======
A tool for manipulating the RecordStore format defined in [`libbiomeval`][1].

How to Build
------------
After building the [`libbiomeval`][1] submodule, execute `make` in the topmost
directory.

Requirements
------------
 * A C++ 2011 compiler (tested with `clang++` and `g++`)
 * A supported operating system (tested with RHEL/CentOS 7.x and macOS 10.13)

Installing
----------
A version compiled from source can be installed via the top-level makefile with
`make install`.

Communication
-------------
If you found a bug and can provide steps to reliably reproduce it, or if you
have a feature request, please
[open an issue](https://github.com/usnistgov/rstool/issues). Other questions may
be addressed to the [project maintainers](mailto:beframework@nist.gov).

Pull Requests
-------------
Thanks for your interest in submitting code to `rstool`. In order to maintain
our project goals, pull requests must:

 * adhere to the existing coding style;
 * use Framework types consistently wherever possible;
 * compile without warning under macOS and RHEL/CentOS 7.x;
 * only make use of POSIX APIs;
 * be in the public domain.

Pull requests may be subject to additional rules as imposed by the National
Institute of Standards and Technology. *Please contact the maintainers*
**before** starting work on or submitting a pull request.

License
-------
`rstool` is released in the public domain. See the
[LICENSE](https://github.com/usnistgov/rstool/blob/master/LICENSE.md)
for details.

[1]: https://github.com/usnistgov/libbiomeval/

