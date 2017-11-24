# sbcl-ci

Automated builds of [sbcl](http://www.sbcl.org/) utilizing their [GitHub Mirror](https://github.com/sbcl/sbcl).

The goal of this project is to enable Continuous Integration support for the SBCL project, and  binary builds on platforms for which it is beneficial (Windows).

This repo contains any scripts necessary to make this happen.

The build server(s) will perform a no-artifact build with each commit to the SBCL repo.
In addition, each official SBCL release will trigger a release to be created on the binary release on its releases page for each SBCL official release.

# License
See [LICENSE](LICENSE.txt)