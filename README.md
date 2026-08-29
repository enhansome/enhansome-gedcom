# awesome-gedcom with stars

> [GEDCOM](https://en.wikipedia.org/wiki/GEDCOM) utilities that will ease the pain

## Contents

* [awesome-gedcom ![](https://awesome.re)](#awesome-gedcom-)
  * [Contents](#contents)
  * [Converters](#converters)
    * [CSV](#csv)
    * [DOT](#dot)
    * [GEDCOM X](#gedcom-x)
    * [JSON](#json)
    * [RDF](#rdf)
    * [SQL](#sql)
    * [XML](#xml)
  * [Editors](#editors)
  * [Tools](#tools)
  * [Parsers](#parsers)
    * [Dart](#dart)
    * [.NET](#net)
    * [Clojure](#clojure)
    * [Go](#go)
    * [Java](#java)
    * [JavaScript/Node.js](#javascriptnodejs)
    * [Objective-C](#objective-c)
    * [PHP](#php)
    * [Python](#python)
    * [R](#r)
    * [Ruby](#ruby)
    * [Rust](#rust)
    * [Scala](#scala)
  * [Visualization](#visualization)
    * [TypeScript](#typescript)
  * [License](#license)

## Converters

### CSV

* [FTAnalyzer](https://github.com/ShammyLevva/FTAnalyzer) ⭐ 65 | 🐛 49 | 🌐 C# | 📅 2026-08-21 - FTAnalyzer let's you export GEDCOM file to .csv file, has GUI, available for Windows and Mac
* [twineconvert](https://twineconvert.com/gedcom-to-csv) - In-browser GEDCOM to CSV converter. No install, no upload, files stay on your device. Preserves family relationships via FAM/INDI ID links and keeps fuzzy dates ("BEF 1850", "ABT JUN 1923") as strings instead of forcing ISO.

### DOT

* [ged2dot](https://github.com/vmiklos/ged2dot) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2026-08-13 - GEDCOM to Graphviz converter

### GEDCOM X

* [gedcom5-conversion](https://github.com/FamilySearch/gedcom5-conversion) ⭐ 35 | 🐛 10 | 🌐 Java | 📅 2024-04-01 - Utilities for GEDCOM 5.5 to GEDCOM X Conversion

### JSON

* [GEDCOMToJSONConverter](https://github.com/PatKayongo/GEDCOMToJSONConverter) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2015-04-29 - Convert GEDCOM genealogy file to a JSON representation
* [twineconvert](https://twineconvert.com/gedcom-to-json) - In-browser GEDCOM to JSON converter. Outputs hierarchical JSON with individuals, families, sources, and event references already linked by ID. Useful for feeding family-tree data into D3, React, or any web visualization without writing a parser.

### RDF

* [GedcomRDF](https://github.com/BruceWhealton/GedcomRDF) ⭐ 6 | 🐛 0 | 🌐 PHP | 📅 2013-06-03 - Gedcom and Genealogy information in Semantic Web format, using RDF serialization format(s)
* [gedcom2sem](https://github.com/jo-pol/gedcom2sem) ⭐ 5 | 🐛 11 | 🌐 Java | 📅 2020-10-12 - Flexible conversion via RDF/TTL to KML/FOAF and other SPARQL queries using LOD
* [gedcom-foaf](https://github.com/bricas/gedcom-foaf) ⭐ 4 | 🐛 0 | 🌐 Perl | 📅 2009-09-17 - Output FOAF files from Gedcom individuals and families

### SQL

* [gedcom-tools](https://github.com/ligurio/gedcom-tools) ⭐ 15 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-01-07

### XML

* [gedcomparser](https://github.com/alfredxiao/gedcomparser) ⭐ 1 | 🐛 1 | 🌐 Groovy | 📅 2013-10-30 - GEDCOM parser, convert an GEDCOM raw data file into XML

***

## Editors

* [Domorium for VS Code](https://marketplace.visualstudio.com/items?itemName=domorium.gedcom) - GEDCOM autocomplete, validation as you type, go to definition and safe XREF rename
* [Domorium for JetBrains IDEs](https://plugins.jetbrains.com/plugin/33323-gedcom) - the same, for IntelliJ IDEA and the rest of the JetBrains platform
* [Domorium for Obsidian](https://community.obsidian.md/plugins/domorium) - edit `.ged` files inside an Obsidian vault, on desktop and mobile
* [Domorium Web](https://domorium.com) - validate and edit a GEDCOM file in the browser with nothing to install; the file is read locally and never uploaded

## Tools

* [AncestryLLM](https://github.com/sodejm/AncestryLLM) ⭐ 4 | 🐛 76 | 🌐 Python | 📅 2026-08-26 - Local-first CLI and interactive tools for researching family history with GEDCOM and RootsMagic data; optional AI assistance is explicit opt-in.

## Parsers

### Dart

* [gedcom-dart](https://github.com/orestesgaolin/gedcom-dart) ⭐ 8 | 🐛 4 | 🌐 Dart | 📅 2026-07-09 - Dart library to parse GEDCOM data

### .NET

* [GEDCOM](https://github.com/prm9894/GEDCOM) ⭐ 13 | 🐛 0 | 🌐 C# | 📅 2014-10-25 - A .NET library that imports data from a .ged (GEDCOM) file

### Clojure

* [gedcom](https://github.com/geni/gedcom) ⚠️ Archived - Clojure GEDCOM library

### Go

* [gedcom](https://github.com/elliotchance/gedcom) ⭐ 124 | 🐛 63 | 🌐 Go | 📅 2024-06-10 ([@elliotchance](https://github.com/elliotchance/)) - library & CLI tools for encoding, decoding, traversing, merging, comparing, querying and publishing GEDCOM files
* [gedcom](https://github.com/iand/gedcom) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2026-05-22 ([@iand](https://github.com/iand/)) - Go package to parse GEDCOM files

### Java

* [Gedcom](https://github.com/FamilySearch/Gedcom) ⭐ 273 | 🐛 118 | 🌐 Python | 📅 2026-08-26 - Gedcom parsers
* [gedcom4j](https://github.com/frizbog/gedcom4j) ⭐ 63 | 🐛 28 | 🌐 Java | 📅 2023-06-13 - gedcom4j is a Java library for parsing and writing GEDCOM 5.5 and 5.5.1 files
* [GedcomStore](https://github.com/thnaeff/GedcomStore) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2022-08-20 - To parse lineage-linked GEDCOM grammar files and build the GEDCOM-structure according to the parsed definitions

### JavaScript/Node.js

* [parse-gedcom](https://github.com/tmcw/parse-gedcom) ⭐ 188 | 🐛 4 | 🌐 TypeScript | 📅 2025-12-14 - A simple GEDCOM parser that focuses on translating GEDCOM structure into JSON
* [gedcom.js](https://github.com/dcapwell/gedcom.js) ⭐ 33 | 🐛 1 | 🌐 JavaScript | 📅 2022-04-18 - Gedcom parser for JavaScript
* [read-gedcom](https://github.com/arbre-app/read-gedcom) ⭐ 26 | 🐛 4 | 🌐 TypeScript | 📅 2025-12-12 - A modern GEDCOM parser with type declarations
* [family-tree-nodejs](https://github.com/woodbri/family-tree-nodejs) ⭐ 21 | 🐛 3 | 🌐 JavaScript | 📅 2024-09-17 - Application for loading GEDCOM files and serving them on the web as navigable family trees
* [gedcom-stream](https://github.com/connrs/gedcom-stream) ⭐ 17 | 🐛 2 | 🌐 JavaScript | 📅 2020-05-05 - A node.js processor for GEDCOM files
* [gedcom-parser](https://github.com/thoughtsunificator/gedcom-parser) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-15 - A tiny GEDCOM parser

### Objective-C

* [Gedcom-Framework](https://github.com/mikkelee/Gedcom-Framework) ⭐ 12 | 🐛 0 | 🌐 Objective-C | 📅 2014-02-07 - Cocoa framework for parsing Gedcom data

### PHP

* [php-gedcom](https://github.com/mrkrstphr/php-gedcom) ⭐ 37 | 🐛 14 | 🌐 PHP | 📅 2022-12-08 - A library for reading and writing GEDCOM files in PHP
* [PHP-GEDCOM-Tools](https://github.com/cfinke/PHP-GEDCOM-Tools) ⭐ 12 | 🐛 0 | 🌐 PHP | 📅 2015-12-06 - PHP scripts for interacting with GEDCOM files
* [gedcom-search](https://github.com/stuporglue/gedcom-search) - PHP search engine for searching GEDCOM files with customizable results weighting

### Python

* [python-gedcom](https://github.com/madprime/python-gedcom) ⭐ 66 | 🐛 4 | 🌐 Python | 📅 2024-01-19 - Python module for parsing, analyzing, and manipulating GEDCOM files
* [simplepyged](https://github.com/dijxtra/simplepyged) ⭐ 41 | 🐛 3 | 🌐 Python | 📅 2019-12-01 - A simple Python GEDCOM parser
* [gedcompy](https://github.com/rory/gedcompy) ⚠️ Archived - Python library to parse and work with GEDCOM (geneology/family tree) files
* [python-gedcom-parser](https://github.com/rootsdev/python-gedcom-parser) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2017-07-16 - Python parser for GEDCOM 5.5 format

### R

* [gedcomS7](https://jl5000.github.io/gedcomS7/) - An R package for handling GEDCOM files

### Ruby

* [gedcom-ruby](https://github.com/binary011010/gedcom-ruby) ⭐ 17 | 🐛 0 | 🌐 Ruby | 📅 2008-12-05 - A Ruby library for easily doing custom, callback-based GEDCOM parsing
* [gedcom](https://github.com/rbur004/gedcom) ⭐ 14 | 🐛 3 | 🌐 Ruby | 📅 2022-04-28 - Ruby Gedcom parser
* [ruby-gedcom-parser](https://github.com/mikefarmer/ruby-gedcom-parser) ⭐ 10 | 🐛 0 | 🌐 Ruby | 📅 2013-09-02 - A simple gedcom parser for ruby

### Rust

* [rust-gedcom](https://github.com/pirtleshell/rust-gedcom) ⭐ 8 | 🐛 5 | 🌐 Rust | 📅 2023-01-05 - Rust library for GEDCOM parsing, with optional serialization to JSON.
* [gedcomx-rs](https://github.com/ephraimkunz/gedcomx-rs/tree/main/gedcomx) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2026-06-19 - Rust library for GEDCOM X parsing, with serialization to / from XML and JSON.

### Scala

* [gedcom](https://github.com/davidmoten/gedcom) ⭐ 4 | 🐛 0 | 🌐 Scala | 📅 2014-01-15 - Scala library to parse GEDCOM files (common genealogy format)

## Visualization

### TypeScript

* [topola-viewer](https://github.com/PeWu/topola-viewer) ⭐ 335 | 🐛 42 | 🌐 TypeScript | 📅 2026-08-09 - interactive genealogy visualization
* [topola](https://github.com/PeWu/topola) ⭐ 122 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-05 - library for embedding genealogy tree visualizations on web pages

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Tod Robbins](https://todrobbins.com) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
