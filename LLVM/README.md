# Swift on Windows Workgroup Domain on Expertise: LLVM

## [Introduction to LLVM](https://www.youtube.com/watch?v=J5xExRGaIIY)

---

[**Introduction:**](https://llvm.org/docs/ProgrammersManual.html#introduction)

This document is meant to highlight some of the important classes and interfaces available in the LLVM source-base. This manual is not intended to explain what LLVM is, how it works, and what LLVM code looks like. It assumes that you know the basics of LLVM and are interested in writing transformations or otherwise analyzing or manipulating the code.

This document should get you oriented so that you can find your way in the continuously growing source code that makes up the LLVM infrastructure. Note that this manual is not intended to serve as a replacement for reading the source code, so if you think there should be a method in one of these classes to do something, but it’s not listed, check the source. Links to the doxygen sources are provided to make this as easy as possible.

The first section of this document describes general information that is useful to know when working in the LLVM infrastructure, and the second describes the Core LLVM classes. In the future this manual will be extended with information describing how to use extension libraries, such as dominator information, CFG traversal routines, and useful utilities like the InstVisitor (doxygen) template.