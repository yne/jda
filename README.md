JDA
===

A ELF/MIPS-R3000 Javascript Disassembler

Goal
-----

My main goal was to understand how disassembler worked.
I choose the MIPS-R3000 because it's a good start for a noob like me.

DONE
----
  - ELF parsing
  - MIPS disassembly
  - GUI (seriously hope you guy like `<select>` and `<input>`)
  - Modification using HTMLElements
  - .text section Repacking

TODO
----
  - Better ELF section management (add/move/remove)
  - Edit non-.text sections too
  - faster GUI (offset based. ATM the whole .text segment is parsed/displayed)

TODO (optional)
---------------
  - why not a decompiler ?
  - why not R4000 ? FPUs are phun ! (jk lol)
