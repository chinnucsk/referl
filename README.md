Referl
======

Referl is tool for refactoring erlang sourse code.

Pretty printer
==============

```erlang
kawaiiprint:file(FileName, [])
```

Not tested
==========

1. Rename
    1. Variable

TODO
====

1. Rename
    1. Function
	3. Record
	4. Recorf field
	5. Macro
	6. Header file
	7. Module file
2. In module action
    1. Generalize function
	2. Reorder parametrs
	3. Function parametrs to tuple
	4. Generate spec
	5. Remove import (can do `erl_tidy`)
3. Move to other file
    1. Macro
	2. Record
	3. Function
4. Expression actions
    1. Eliminate variable
	2. Merge expressions
	3. Inline function
	4. Extract function
	5. Inline macro
	6. Tuple to record
5. Using `erl_tidy`
