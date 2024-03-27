### v4.0.0 (2024-03-27)

* Revise API: `val generate : ?g:g -> int -> string`, and
  `val generate_into : ?g:g -> bytes -> ?off:int -> int -> unit`
  Remove cstruct dependency (#15 @hannesm)

### v3.0.0 (2021-11-15)

* Remove Mirage_random.C (#14 @hannesm)

### v2.0.0 (2019-10-21)

* Specialise buffer to Cstruct.t directly in Mirage_random.S (#12 @hannesm)
* Deprecate Mirage_random.C (#12 @hannesm)
* Raise lower bound of OCaml to 4.06.0 (#12 @hannesm)

### v1.2.0 (2018-11-11)

* Move Stdlibrandom to a separate package, mirage-random-stdlib
* Port to dune

### v1.1.0 (2017-06-15)

* Port to Jbuilder

### v1.0.0 (2016-12-20)

* Initial version, code imported from https://github.com/mirage/mirage
