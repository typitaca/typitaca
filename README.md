# Typitaca

The Typitaca is a collection of software packages, tools,
and libraries that create a common platform for using and
developing applications in Common Lisp.

## Motivation

This project proposes a distribution format as
the next generation Common Lisp ecosystem.
In the traditional ecosystem, conflicting dependencies
between libraries and lack of documentation have been problems.
Therefore, the project aim to provide users with a well-tested,
well-documented and consistent Common Lisp environment
through regular distribution formats such as Haskell, Racket, and TeX.

## Policy

- Test all libraries.
- Provide source code.
- Provide documents for all libraries.
- Updates libraries every 6 months.
- Support no libraries out of the distribution.

## Packages

- SBCL

## Notice

Thank you for all the interest in this project.
However, do understand that this is very much
a non-functional prototype. There's a huge amount of heavy lifting to do.
Unless you are participating in that, please maintain radio silence on GitHub.
This includes submitting trivial PRs (like improving README build instructions).

## Development

You need to install the following softwares.

- [vale](https://github.com/errata-ai/vale) -
  Vale is a syntax-aware linter for prose built
  with speed and extensibility in mind.
- [editorconfig](https://editorconfig.org/) -
  EditorConfig helps maintain consistent coding styles for multiple developers
  working on the same project across various editors and IDEs. 
- [roswell](https://github.com/roswell/roswell) -
  Roswell is a Lisp implementation installer/manager, launcher, and much more!

## Copyright

Copyright 2020, Typitaca developers All Rights reserved.

The scripts for configuring the Typitaca distribution are published
under the MIT license. The licenses for the libraries and processing systems
included in the distribution follow the licenses specified by each project.
