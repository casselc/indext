# casselc/indext

`indext` is a Clojure library for constructing and using external indices on unstructured data.

It is an implementation of the concept in the Clojure Conj 2023 talk [Gaining Constant Time Lookup Over Unorganized Data](https://www.youtube.com/watch?v=8XgY1j1etOI) presented by Ghadi Shayban and developed by Jeb Beich, Ghadi Shayban, and others at Nubank.

## Library Status

**Current Status:** Aspirational

This library is an early work in progress, the goal is for the initial implementation to hew to the concepts presented in the talk as faithfully as possible, reusing the dataset abstraction and using Bagwell's Ideal Hash Trees as the basis of the on-disk representation.

Future versions of the library will provide conveniences for constructing indices from data sources such as fixed-length record files, line-delimited files, CSVs, etc. It may also explore additional on-disk representations and hashing strategies such as [CHAMPs](https://michael.steindorfer.name/publications/oopsla15.pdf) or [PTHash](https://ieeexplore.ieee.org/abstract/document/10210677).

## Usage

Scroll back a few lines and review the library's current status.

## License

Distributed under the Mozilla Public License version 2.0.
