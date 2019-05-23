dlang-stdx
==========

The dlang-stdx organization is the growth place for new standard library D modules.
The projects hosted by this organization are available via Dub and are considered candidates for inclusion to the standard library or runtime.
This means that any testing and feedback is very appreciated as the end goal is to have fully matured projects.

The main advantages over `std.experimental` are:
- semantic versioning
- directly testable and usable by the D community (via `dub`)
- individual projects for fine-grained control and management
- bug fixes can be shipped immediately

Common guidelines
-----------------

As the projects are candidates for inclusion to the standard library,
a few common standard are expected:

- [ ] SemVer releases
- [ ] available on the Dub registry
- [ ] compilable with at least the latest DMD and LDC releases
- [ ] common top-level namespace (`stdx`)
- [ ] easy to access documentation build ([example](https://dlang-stdx.github.io/collections))
- [ ] no dependence on projects outside the standard library and dlang-stdx for the normal build (e.g. `unit-tested` can still be used). This will greatly help when a project has matured enough for inclusion in the standard library.
- [ ] same license `BSL 1.0`
- [ ] [DStyle](https://dlang.org/dstyle) + static linting with [D-Scanner](https://github.com/dlang-community/D-Scanner)
- [ ] [`.editorconfig`](https://github.com/dlang-stdx/collections/blob/master/.editorconfig)
- [ ] inclusion on the [Project Tester](https://github.com/dlang/ci)

Some of these guidelines like the inclusion on the Project Tester can be added after a project has been moved to this organization.

Inclusion
---------

Projects who seek to become eventually part of the D standard library are invited to join this organization
provided their project conforms to the common guidelines below.
The [issue tracker of this meta repository](https://github.com/dlang-stdx/meta/issues) can be used to request and discuss an inclusion.

Absence
-------

If a project has received no development within a year and:
- there are still outstanding design issues
- the author(s) are unavailable
- no one else is willing to continue the project

Then the project will be moved out of this organization.
