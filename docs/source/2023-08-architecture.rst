2023-08 (August 2023) Architecture
===================================

*Aug 30 14:59*

1. Remove Pipeline(s)
  - Process starting with conversion of a lot of things to Operations
  
  - Process continuing with the introduction of CompilerDriven
  
  - `*StageProcess`es may remain until I figure out the attraction 
    of the abstraction

2. Queries

  - Need to add `QueryDatabase` and maybe `ElijahObject` (or `EOR_Registry`).

    * Need easy serialization format/code 

    * (annotations, clojure, python)

    * Amazon ION, Clojure EDN

3. PipelineAccess and CompilerEnclosure

4. Version Control

  - Only some/same `COMP` result hashing (not perfect ;) 

5. Post Processing of "AST"

  - A little bit of interfaces added/converted, but none done for "AST"

  - Source Model (`SM_`*) should come up later

Principles
-----------

* Statements

  - Put `EG_Statement` in more places

* Operations

  - Put `Operation` and `Operation2` in more places

* Steps

  - Break things down into steps, sometimes with shared state

  - Presumably for Web interface

  - Hopefully will see "unification of architecture" soon

Notes
------

1. Path

  - Curiously still skipped

2. Incremental Compiler/Library

  - Language switching not implemented (`Rust`, `OCaml`, `Clojure`, `Scala`), but feelers 
  with `mal`?
