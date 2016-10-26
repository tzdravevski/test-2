![Stencila](http://static.stenci.la/img/logo-name-400x88.png)

A small repository is for testing Stencila's integrations with Git, Github and Travis CI etc. We use it for:

- testing that our [C++ interface](https://github.com/stencila/stencila/blob/master/cpp/stencila/git.hpp) to [libgit2](https://libgit2.github.com/) is working properly (see [`stencila/cpp/tests/git.cpp`](https://github.com/stencila/stencila/blob/master/cpp/tests/git.cpp))

- testing our Github authentication and authorization integration

- trying little things out on [Travis CI](travis-ci.org/stencila/test) (like: "Does the Trusty beta build environment use Python with 4-btye Unicode support?") without polluting our other repos with lots of commits.
