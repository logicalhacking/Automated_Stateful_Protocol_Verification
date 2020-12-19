# Automated Stateful Protocol Verification

This git repository contains a local mirror of
[Stateful Protocol Composition and Typing](https://www.isa-afp.org/entries/Automated_Stateful_Protocol_Verification.html)
entry of the
[Archive of Formal Proofs (AFP)](https://www.isa-afp.org).

The official AFP releases are tagged. Additionally, this repository
may contain extensions (i.e., a development version) that may be
submitted (as an update of the Automated Stateful Protocol Verification
entry) at a later stage.

## Installation

This project depends on another [AFP](https://www.isa-afp.org) entry: 
[Stateful Protocol Composition and Typing](https://www.isa-afp.org/entries/Stateful_Protocol_Composition_and_Typing.html). 
Please follow the [official guidelines](https://www.isa-afp.org/using.shtml)
for installing the AFP locally. For short:
* [Download](https://www.isa-afp.org/release/afp-current.tar.gz) the complete AFP
* Extract the downloaded archive to an directory of your choice
* Let's assume the extracted archive lives in `/home/isabelle/afp`, now execute:

```console
achim@logicalhacking:~$ echo "/home/isabelle/afp/thys" >> ~/.isabelle/Isabelle2020/ROOTS
```

## How to build

```console
achim@logicalhacking:~$ isabelle build -D Automated_Stateful_Protocol_Verification
```

## Authors

* Andreas V. Hess
* [Sebastian Mödersheim](https://people.compute.dtu.dk/samo/)
* [Achim D. Brucker](http://www.brucker.ch/)
* [Anders Schlichtkrull](https://people.compute.dtu.dk/andschl/)

## License

This project is licensed under a 3-clause BSD-style license.

SPDX-License-Identifier: BSD-3-Clause

## Master Repository

The master git repository for this project is hosted by the [Software
Assurance & Security Research Team](https://logicalhacking.com) at
<https://git.logicalhacking.com/afp-mirror/Automated_Stateful_Protocol_Verification>.

## Publications

* Andreas V. Hess, Sebastian Mödersheim, Achim D. Brucker, and Anders
  Schlichtkrull. Performing Security Proofs of Stateful Protocols. In
  34th IEEE Computer Security Foundations Symposium (CSF). , IEEE,
  2021.
  https://www.brucker.ch/bibliography/abstract/brucker.ea-web-components-2019

* Andreas V. Hess, Sebastian Mödersheim, Achim D. Brucker, and Anders
  Schlichtkrull. Automated Stateful Protocol Verification. In Archive 
  of Formal Proofs, 2020. 
  <http://www.isa-afp.org/entries/Automated_Stateful_Protocol_Verification.html>, 
  Formal proof development
