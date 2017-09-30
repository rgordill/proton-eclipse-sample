# QPID recv example to build a container for testing

## Intro

This example is extracted "as is" from qpid proton c++ examples.

## Version

Current version used from Fedora epel

- qpid-proton-c-0.17.0-4.el7.x86_64
- qpid-proton-cpp-devel-0.17.0-4.el7.x86_64
- qpid-proton-c-docs-0.17.0-4.el7.noarch
- qpid-proton-cpp-0.17.0-4.el7.x86_64
- qpid-proton-cpp-docs-0.17.0-4.el7.noarch
- qpid-proton-c-devel-0.17.0-4.el7.x86_64

## Extra notes for eclipse

Add _GLIBCXX_USE_CXX11_ABI=0 in cpp preprocessor directives to avoid linking problems