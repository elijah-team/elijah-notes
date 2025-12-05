Packages
=========

ci
***

Contains "Compiler Instructions".  This models the `.ez files`, mostly letting the compiler know what directories to find source in (and possibly under what conditions).

comp
*****

Contains the compiler driver, especially the entry point.

comp/functionality
*******************

"Metapackage"

comp/functionality/f202
************************

comp/internal
**************

Holds `CompilationImpl` I believe.

contexts
*********

Contains the lookup logic to turn "names" into "elements".

diagnostic
***********

Contains mainly the interface for "errors" that are reported by the compiler.

These errors can be output in the terminal, or if they are `Locatable`, can be used like "markers" in the Eclipse Workbench.

entrypoints
************

Contains `MainClassEntryPoint` and `ArbitraryFunctionEntryPoint`.  These represent the entry points into the program (as opposed to the compiler).

`Entrypoint`s represent the "surface" of the code that is generated.  Beyond an entrypoint, there are no guarantees that the code will be usable.  
This provides flexibility to the "Generator" implementations, allowing them to just "do what works".

Specifically, I don't know how this will work for C/C++ generation and garbage collectors...

gen
****


lang
*****

lang/builder
*************

lang/imports
*************

lang2
******

nextgen
********

nextgen/inputtree
******************

nextgen/outputstatement
************************

nextgen/outputtree
*******************

stages
*******

stages/deduce
**************

stages/deduce/declarations
***************************

stages/deduce/fluffy
*********************

This package holds "Fluffy". subpackages are `i` for interfaces and `impl` for implementations.

stages/gen_c
*************

stages/gen_fn
**************

stages/gen_generic
*******************

stages/generate
****************

stages/instructions
********************

stages/logging
***************

stages/translate
*****************

testing
********

util
*****

work
*****

