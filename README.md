Cb (pronounced C flat, working name) is a strict, imperative language with a
C-like syntax designed to support precise GC and to serve as a target
language for higher level languages.

It does not have an object system but is designed such that an object system
could easily be built for a language that uses Cb as a target.

It does not have algebraic data types, but again the design is intended to
support easily building support for algebraic data types in a language
implementation that targets Cb.

As you may have realized, Cb is distinguished more by the features it doesn't
provide than the ones it does.

Built-in Types
==============

* int8, uint8, int16, uint16, int32, uint32, int64, unit64, intptr 
* _type_* where _type_ is a builtin or user-defined type.
* _type_[] where _type_ is a builtin or user-defined type. 
