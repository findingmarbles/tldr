# gcc

> Preprocesses and compiles C and C++ source files, then assembles and links them together.

- Compile multiple source files into executable:

`gcc {{source1.c}} {{source2.c}} -o {{executable}}`

- Allow warnings, debug symbols in output:

`gcc {{source.c}} -Wall -Og -o {{executable}}`

- Include libraries from a different path:

`gcc {{source.c}} -o {{executable}} -I{{header_path}} -L{{library_path}} -l{{library_name}}`
